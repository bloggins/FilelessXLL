*code borrowed from: https://github.com/MitchHS

added function:
'''
extern "C" {
    void __declspec(dllexport) xlAutoOpen();
    void xlAutoOpen() {

        do_stuff();
    }
}
'''
