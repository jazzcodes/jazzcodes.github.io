# Almost Done with the Website

Today, I continued the the18design website and made the following components.

1. Footer 

Mobile footer was already made yesterday. Worked on desktop version. Studied `order` property in flex-items and it was quite easy to order the items accordingly on different screen sizes. However, manipulating their widths was quite a task.. so managed it accordingly as per different screen sizes. 


2. Mobile Menu

Worked on mobile menu. Used JS to add functionality to Open and Close button of the mobile menu. Made it myself as it wasn't given in the design.

    const menu=document.querySelector(".menu");
    const cross=document.querySelector(".cross");
    const mobileMenu=document.querySelector(".nav-ul-mobile");

    function openMenu()
    {
        menu.style.display="none";
        cross.style.display="initial";
        mobileMenu.style.display="flex";

    }

    function closeMenu()
    {
        menu.style.display="initial";
        cross.style.display="none";
        mobileMenu.style.display="none";

    }

    menu.addEventListener("click", openMenu);
    cross.addEventListener("click", closeMenu);
    
    
  3. Fonts

  Installed fonts from a [website](https://pangrampangram.com/products/neue-machina).
  Then used the below syntax to add normal and bold versions of the font

    @font-face {
        font-family: customFontsRegular;
        src: url(../fonts/PPNeueMachina-InktrapRegular.otf);
    }

    @font-face {
        font-family: customFontsBold;
        src: url(../fonts/PPNeueMachina-InktrapUltrabold.otf);
    }


Further, made some final changes to make the design look same as the figma design. 
There are some final things due for tomorrow -> exact appearance and hover states.

The code can be found [here](https://github.com/jazzcodes/the18Design/pull/8).
The site is active [here](https://jazzcodes.github.io/the18Design/).

Till then byes! :D
