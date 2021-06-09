# Iosevka Wizard

This is my custom build of the Iosevka  font. The build file was generated through [this](https://typeof.net/Iosevka/customizer)

# Building the font

I prefer using the provided docker container, other instructions [here](https://github.com/be5invis/Iosevka#customized-build).

If you are using the fish shell:

    docker run -e FONT_VERSION=7.0.4 -it -v (pwd):/build avivace/iosevka-build ttf::iosevka-wizard-term

Other shells:

    docker run -e FONT_VERSION=7.0.4 -it -v (pwd):/build avivace/iosevka-build ttf::iosevka-wizard-term
