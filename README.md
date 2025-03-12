# Pump It Up Keyboard Hook

Tool that allows you to use your keyboard on Pump It Up.
Thanks to TheRatHatter!

Tested on Pump It Up Fiesta 2, Prime 1 and Prime 2. To modify the keys, edit the `binds` list in `hook.cpp`.

# Usage
Download the pre-compiled binary or compile it, then add it to LD_PRELOAD before executing Prime.

# Default keys
F1 for test, F2 for service, F5 for player 1 coin, F6 for player 2 coin

Pad layout:
```
Q   E   R   Y
  S       G
Z   C   V   N
Pad 1   Pad 2
PAD 1 BONUS : MANIA LAYOUT 56789
```

# Compiling

Requires an atleast C++11 compliant compiler.

To compile it yourself, run these commands:

```
sudo apt-get install git build-essential libx11-dev
git clone https://github.com/RhapsodiaID/piu-kb-hook
cd piu-kb-hook
make
```

You'll now have a `hook.so` file in the aforementioned directory.
