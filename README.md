0. Bağılmılıkların kurulumu (Debian-based için)


```bash
sudo dpkg --add-architecture i386 ; sudo apt update
```


```bash
sudo apt install lldb libstdc++-12-dev:i386 libstdc++-11-dev:i386 git make gcc-multilib mesa-common-dev cmake clang
```

1. Bu depoyu klonlayın.
2. SDK'yı indirin:

    ```bash
     mkdir sdk
     git clone https://github.com/ValveSoftware/halflife.git sdk/halflife-master
    ```

3. Derleme klasörünü hazırlayın:

    ```bash
     mkdir build
     cd build
     cmake ..
    ```

4. Derleyin:

    ```bash
     make
    ```

5. Oyunu başlatın.
6. Hileyi enjekte edin. (derleme klasöründe olduğunuzdan emin olun)

    ```bash
     ./injector.sh load
    ```
credits: https://github.com/UnkwUsr/hlhax
