2 Stage-Opamp:
The road for the expanding market of sophisticated
electronics applications in mobiles and sensor applications
was created by the recent development in CMOS scaling. The
integration of complicated functionalities on a single chip
(such as a SOC (System on Chip)), along with ongoing
increases in operating speed and decreases in system power
consumption, is what drives scaling.
Transistor dimensions are getting smaller as a result of
improvements in CMOS manufacturing techniques. The
advantages of adopting smaller dimension transistors
typically result in lower power consumption, smaller device
sizes, and higher performance at high frequencies.
Transconductance and output resistance, two crucial analog
properties of a transistor, will decrease as a result of the use
of tiny CMOS technologies.
Analog circuits frequently employ operational amplifiers
(op-amps) with negative feedback to create amplifiers with a
variety of desirable characteristics, including steady gain,
good linearity, and low output impedance. However, the
negative feedback's significant phase lag causes a stability
(STB) problem. The STB of the amplifier has been improved
using a variety of approaches,when we observe the second order system’s time
response with step input, we see that larger phase margin
results in reduced oscillations in the output signal.
we prefer to have ringing as minimum as possible. A
minimum of 45 degrees phase margin is desirable and a 60
degree PM is mostly preferred. Frequency correction must be carried out to improvise the
stability and provide proper transient step responsiveness.
Miller and cascode compensations are well-known
approaches. Miller compensation is well known for its ability
to increase bandwidth via pole splitting phenomenon. We
will be employing miller compensation in our dual-stage
opamp and observe the results with high gain and improved
phase margin. Though miller compensation is used to
enhance the gain bandwidth product, complexity has also
risen as a result of interims of extra amplifier stages and
capacitors. The stability is compromised by the right halfzero (RHP) that is introduced by Miller compensating with a
nulling resistor.

<img width="698" height="550" alt="image" src="https://github.com/user-attachments/assets/3034f410-9eaa-4251-8f14-49a84763dffe" />

<img width="700" height="559" alt="image" src="https://github.com/user-attachments/assets/89d9d31e-0ccc-4b43-b729-47abfbaab82e" />


Conclusion:
Highlights the drawbacks of
uncompensated two stage opamp design. It signifies the
improvement brought out in two stage opamp design by
using miller compensation and implements miller
compensation in designing two stage opamp highlighting
improved parameters. The aspect ratio values obtained from
calculation shows better DC gain, Phase Margin and Gain
Bandwidth Product of the implemented dual stage
operational amplifier.
