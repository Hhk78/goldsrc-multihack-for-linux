# goldsrc-hack-cstrike
Bu hile, goldsource motoruna dayalı oyunlar için bir linux hack'idir, bu nedenle birçok oyun, diğer adıyla half-life 1, counter-strike 1.6, vb. için çalışabilir. Özellikler listesi için src/funcs'a bakın.

# Başlangıç
Bağılmılıkların kurulumu (Debian-based için)
```sudo dpkg --add-architectur i386 ; sudo apt update```

```sudo apt install lldb libstdc++-12-dev:i386 libstdc++-11-dev:i386 git make gcc-multilib mesa-common-dev cmake clang```

```git clone https://github.com/Hhk78/goldsrc-hack-cstrike.git```

SDK'yı indirin:

```bash
mkdir sdk```
 ```bash
git clone https://github.com/ValveSoftware/halflife.git sdk/halflife-master```
 Derleme klasörünü hazırlayın:
 ```bash
mkdir build
 cd build
 cmake ..```
 Oyunu başlatın ve hileyi enjekte edin (derleme klasöründe olduğunuzdan emin olun).
 ```bash
 ./injector.sh load```
