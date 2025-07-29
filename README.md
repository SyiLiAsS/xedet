## Build

This project uses [Meson](https://mesonbuild.com/) as its build system.

### Steps to build:

1. Ensure you have Meson installed.  
On Debian/Ubuntu:  
    ```bash
    sudo apt install meson
    ```

2. Configure the build directory:

    ```bash
    meson setup builddir
    ```

3. Build the project:

    ```bash
    meson compile -C builddir
    ```

4. (Optional) Run the executable (if applicable):

    ```bash
    ./builddir/xedet
    ```

