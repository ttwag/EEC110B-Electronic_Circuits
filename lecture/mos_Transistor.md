# MOS Transistor

## Summary

**NMOS**

**PMOS**

Regions of Operation
* Saturation: $V_{DS}\leq V_{GS} - V_{TH}$
* Edge of Saturation: $V_{DS} = V_{GS} - V_{TH}$
* Triode: $V_{DS} > V_{GS} - V_{TH}$

Large Signal Model

$$I_{D, Sat} = \frac{1}{2}\mu_p C_{ox} \frac{W}{L}(V_{GS} - V_{THP})^2 (1-\lambda V_{DS})$$

$$I_{D, Triode} = \frac{1}{2}\mu_p C_{ox} \frac{W}{L} [2(V_{GS} - V_{THP})V_{DS} - V_{DS}^2]$$

Small Signal Model - Same for NMOS and PMOS





## NMOS Region of Operations - Saturation

$$V_{GS} > V_{TH}$$

$$V_{DS} > V_{GS} - V_{TH}$$ or $$V_{GD} < V_{TH}$$

## Large Signal

## Small Signal

## Transconductance

$g_m$ or transconductance is a measure of how much drain current changes for a given change in $V_{GS}$

$$g_m = \frac{\partial I_D}{\partial V_{GS}} = \mu_n C_{ox} \frac{W}{L} (V_{GS} - V_{TH})$$

$g_m$ is the slope of $I_D$ $V_{GS}$ graph

$g_m$'s value depends on what parameter the designer keeps constant.

For a constant $I_D$, 

$$g_m = \sqrt{2 \mu_n C_{ox} \frac{W}{L} I_D}$$

For a constant $V_{GS} - V_{TH}$

$$g_m = \frac{2I_D}{V_{GS} - V_{TH}}$$

Increasing the width of MOSFET is equivalent to putting them in parallel, and this increases the $g_m$

## Channel Length Modulation

## NMOS Region of Operations - Deep Triode

## NMOS Region of Operations - Triode

$$V_{GS} > V_{TH}$$

$$V_{DS} < V_{GS} - V_{TH}$$ or $$V_{GD} > V_{TH}$$
