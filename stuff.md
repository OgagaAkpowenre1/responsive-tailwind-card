tailwind.config = {
    theme: {
        extend: {
            colors: {
            pale_orange: '#ffd9a6',
            light_orange: '#fbb03b', 
            orange: '#f7931e',
            },
            fontFamily: {
                sans: ['Josefin Sans', 'sans-serif'],
                title: ['Playfair Display SC', 'serif']
            },
            backgroundImage: {
                bg_desktop: "url('bg-desktop.png')",
                bg_mobile: "url('bg-mobile.png')"
            }
        }
    }
}

bg-gradient-to-r from-custom_green to-blue-200
bg-gradient-to-tr from-custom_purple to-custom_pink