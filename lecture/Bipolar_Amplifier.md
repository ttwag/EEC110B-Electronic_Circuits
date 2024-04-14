# Bipolar Amplifier

A voltage-controlled current source can form an amplifier, and here are some metrics that evaluate the performance of the amplifier:
* **Power Dissipation** - Determines the battery lifetime
* **Speed** - Operating frequency
* **Noise** - Amplifier introduces noise

## I/O Resistance

An ideal voltage amplifier has an input that acts as a voltmeter, which senses the voltage without disturbing (loading) the preceding stage.

The ideal **input impedance is infinite**

At the output, the circuit will be connected in parallel to the output. Therefore, it should have a **zero output impedance** to not create a voltage divider.

We can analyze the I/O impedance by applying a test voltage $V_X$ and dividing it by the current.

![Figure6](./image/Figure6.png)

Here's an example of calculating the input impedance:

![Figure7](./image/Figure7.png)


## Common-Emitter Amplifier with Degeneration

* Pro: More stable DC 
* Con: low gain

$$A_v = -\frac{g_m R_c}{1 + R_E(\frac{1}{r_{\pi}} + g_m)}$$

Since $g_m >> \frac{1}{r_{\pi}}$

we have

$$A_v = -\frac{R_c}{\frac{1}{g_m} + R_E}$$

$$R_{in} = r_{\pi} + (\beta + 1) R_E$$

$R_{out} = R_c$, $V_A -> \infty$

$V_A \neq \infty$

$$R_{out} = [1 + g_m (R_E || r_{\pi})]r_o + R_E || r_{\pi}$$

when $g_m r_o >> 1$

$$R_{out} = [1 + g_m (R_E || r_{\pi})]r_o$$ 


