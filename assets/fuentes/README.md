# Image sources

The PNGs in `assets/` are rendered from these HTML files with headless Chrome at 2x:

    chrome --headless=new --hide-scrollbars --force-device-scale-factor=2 --window-size=1280,400 --screenshot=hero-oscuro.png hero-oscuro.html
    chrome --headless=new --hide-scrollbars --default-background-color=00000000 --force-device-scale-factor=2 --window-size=600,330 --screenshot=chatty-oscuro.png chatty-oscuro.html
