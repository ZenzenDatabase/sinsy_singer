# sinsy_singer

Dependency packages:

1. https://sourceforge.net/projects/sinsy/files/
1. https://github.com/GloomyGrave/Sinsy-NG
1. https://github.com/GloomyGrave/libespeak-NG
1. https://github.com/espeak-ng/pcaudiolib
    
        The Portable C Audio Library (pcaudiolib) provides a C API to different audio devices. It supports:
    
1. https://github.com/espeak-ng/sonic

**Some bugs**

1. bugs:

        ./sinsyNG: symbol lookup error: ./sinsyNG: undefined symbol: sinsy_ng_addRest

It works, but cannot generate the \wav\

    LD_LIBRARY_PATH=/usr/lib ./sinsyNG -o a.wav a.xml 
    or you can do this:
        export LD_LIBRARY_PATH=/usr/lib/


Command line:
            
            /sinsyNG -o en_test.wav -m en en_test.xml
