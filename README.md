# brain isn't recognized on linux
1. go to /etc/udev/rules.d
2. make a new file called 10-vex.rules   (or something that starts with a low number and ends with .rules)
3. add this code:
```
# allow user rw access to serial ports
KERNEL=="ttyACM[0-9]*",MODE="0666"
```

# clawbot
<img width="317" alt="Screenshot 2023-12-19 at 10 40 18 AM" src="https://github.com/woodstockcs/clawbot/assets/7727226/731a24f6-72ec-40cb-9503-c0054fbefb28">


![Screenshot 2023-12-19 9 39 11 AM](https://github.com/woodstockcs/clawbot/assets/7727226/ddea905e-2497-408e-9fbd-0f281a3ec9c2)
