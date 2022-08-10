# iiitb_digAClock -> Alarm Clock Implementation using Verilog

A digital clock with an alarm feature implemented
using Verilog is presented in this paper. The clock design can be
fully implemented on an FPGA. The module outputs the time
in an HH-MM-SS (Hour-Minute-Second) format along with an
alarm indicator, which gets set to HIGH when the clock reaches
the time set by the user before. A test bench was also made along
with the aforementioned. The design was tested on this test bench
using Icarus Verilog, and simulated using GTK-Wave

## Appliications
- Real time Digital Clock
- Can be Systhesized with FPGA design
- Used as an alarm in time-sensetive systems

## Block Diagram

![alarm1](https://user-images.githubusercontent.com/75616591/183852232-f9762185-c0a9-4fa3-9708-2f1ea366c0a5.jpg)

## Tool Installation Instructions

For Ubuntu :

```
$   sudo apt-get update
$   sudo apt-get install iverilog gtkwave
```

### Instructions to run

```
$   sudo apt install -y git
$   git clone https://github.com/hypnotic2402/iiitb_digAClock
$   cd iiitb_digAClock
$   iverilog iiitb_clock.v iiitb_aclock_tb.v
$   ./a.out
$   gtkwave test.vcd
```

## Functional Characteristics

Results obtained on testing alarm clock against the test-bench:


![Screenshot from 2022-08-03 23-21-02](https://user-images.githubusercontent.com/75616591/183854082-2c88f0df-2b77-4e2a-b49a-4771b0b55bba.png)

## Contributers

- Saket Gurjar
- Kunal Ghosh

## Acknowledgments

- Kunal Ghosh, Director, VSD Corp. Pvt. Ltd.

## Contact Information

- Saket Gurjar, IMTech 2020, International Institute of Information Technology, Bangalore : Saket.Gurjar@iiitb.ac.in
- Kunal Ghosh, Director, VSD Corp. Pvt. Ltd. kunalghosh@gmail.com

## Referemces

https://www.fpga4student.com/2016/11/verilog-code-for-alarm-clock-on-fpga.html
