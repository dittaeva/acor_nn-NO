acor_nn-NO
==========

Draft Norwegian Nynorsk autocorrection package for OpenOffice, LibreOffice, etc. Based on acor_en-US.dat in LibreOffice 3.6.2.2.

To do
------

1. Add license from Libreoffice 3.6.2.2.

To use
------

    git clone --depth=1 https://github.com/dittaeva/acor_nn-NO.git
    cd acor_nn-NO
    zip -r acor_nn-NO.dat *
    mv acor_nn-NO.dat ~/.config/libreoffice/3/user/autocorr/ # or wherever else you have your Libre/OpenOffice settings.
