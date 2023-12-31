# Crypto_AES-256

Download Crypto++:
Go to the official Crypto++ website at https://www.cryptopp.com/ and find the download link. You'll usually find links to source packages. Download the appropriate source package.

Extract the Package:
After downloading the package, extract it using an archive utility (like WinRAR or 7-Zip on Windows, or tar on Linux).

Compile the Library:
To compile Crypto++, follow the platform-specific and compiler-specific instructions. Typically, you'll need to run commands like make or use a build system like CMake.

For example, on Linux, you can do the following:

bash

    cd cryptoppX.XX  # Enter the directory created after extraction
    make              # Compile the library
    sudo make install # Install the library (optional)

    If you're using Windows and Visual Studio, follow the specific instructions for compiling with Visual Studio.

    Link with Your Project:
    After compiling the library, you need to link it with your project to use Crypto++ features. Add the path to the Crypto++ header files and library files to your project's configuration.

Depending on your platform and compiler, there might be slight variations in the steps mentioned above. Make sure to consult the Crypto++ documentation for detailed installation and compilation instructions on your platform.
