# 💡 Soney

This project is a set of custom, extensible speakers I built for a small portable shop that I designed and constructed.

About a decade ago, I built a TDA2003 20W bridged mono amplifier from a kit. At the time, I didn’t have a clear use for it, so it ended up in storage. When I recently finished building my small shop, I realized it was the perfect opportunity to bring that amp back to life.

My goal was to create a single, “good enough” speaker system for listening to music or podcasts while working on woodworking or electronics projects.

I also wanted the system to be flexible:

- Additional speakers can be daisy-chained.
- The speakers can be powered either by the built-in amplifier or by an external amplifier.

The result is a modular, practical audio setup tailored specifically for a small workshop environment. To improve transient power response and DC input filtering, I added an additional capacitor bank on a separate PCB.

> If you found this project useful, interesting, or worth keeping an eye on, consider giving it a ⭐️.
> It helps others discover the project and motivates me to keep building and sharing more.

## 🔹 Construction

![Soney 1](<Construction/Soney 1.jpg>)

![Soney 2](<Construction/Soney 2.jpg>)

![Soney 3](<Construction/Soney 3.jpg>)

![Soney 4](<Construction/Soney 4.jpg>)

![Soney 5](<Construction/Soney 5.jpg>)

## 🔹 Rev 1 Schematic

![Rev 1](<Schematics/Rev 1.png>)

## 🔹 Rev 1

- Initial release.

## 🔹 General Notes

- Multiway 6×9 speakers were used to achieve decent sound while minimizing space.
- Black anodized rods on the back panel provide convenient cable-wrapping points.
- The amplifier kit is mono, so the left and right input channels are passively summed to a single output.
- Additional daisy-chained speakers are wired in series to prevent overloading the TDA2003 amplifiers.
- If speakers are connected in parallel, the minimum impedance is determined by the internal 4 Ω speaker.
- The TDA2003 can deliver up to 3.5 A of repetitive peak output current and up to 4.5 A of non-repetitive peak current. The fuse should be sized accordingly.

##

> Educational Use Notice: This project is provided for educational and learning purposes only. You are welcome to read, study, and experiment
> with this software and/or hardware. It is not intended for commercial use. This software and/or hardware is provided "as is", without warranty
> of any kind. The author assumes no responsibility for any damages or issues resulting from its use.