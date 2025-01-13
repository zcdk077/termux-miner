# CPUMINER-MULTI
<a href=https://moneyblink.com/6sVz>Original Script</a>

# ANDROID SMARTPHONE

## Bahan-Bahan Mining
1. <a href=https://moneyblink.com/UhQzhTymk>Termux</a>
2. <a href=https://moneyblink.com/7kzerY1eXJx1>AutoStart Manager</a> <br><br>

A. TUTORIAL TERMUX

## [ Install Update & Upgrade ]

```
yes | pkg update && pkg upgrade -y
```

## [ Install Builds ]

```
yes | pkg install wget curl proot tar nano
```

## [ Autorun Ubuntu ]

```
nano ../usr/etc/bash.bashrc
```

## [ Copy dan paste dibaris paling bawah ]

```
termux-wake-lock
clear
./start-ubuntu.sh
```

## [ Install Ubuntu ]

```
wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu/ubuntu.sh -O ubuntu.sh && chmod +x ubuntu.sh && bash ubuntu.sh && clear && ./start-ubuntu.sh
```

B. TUTORIAL UBUNTU

## [ Install Update & Upgrade ]

```
yes | apt-get update && apt-get upgrade -y
```

## [ Install Builds ]

```
apt-get install git proot nano automake autoconf pkg-config libcurl4-openssl-dev libjansson-dev libssl-dev libgmp-dev zlib1g-dev make g++
```

## [ Clone & Install CPUMiner-Multi ]
```
git clone https://github.com/zcdk077/cpuminer-multi && cd cpuminer-multi && chmod +x start.sh && ./build-linux-arm.sh
```

## [ Edit Wallet ]
```
nano start.sh
```

## [ Start CPUMiner-Multi ]
```
./start.sh
```

## [ Autorun Mining ]

```
cd .. && nano ../etc/bash.bashrc
```

## [ Copy dan paste dibaris paling bawah ]

```
clear
cd cpuminer-multi/&&./start.sh
```

Jika tidak mengerti tentang autorun bisa melewati langkah ## [ Autorun Ubuntu ] dan [ Autorun Mining ]
