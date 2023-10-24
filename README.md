# QKD_LBS
QKD simulator for different atmospheric conditions
This simulator was created using Mathematica and the budget link equation to simulate the key rate obtained at various distances for different types of locations. We have taken several constants in our simulations:

1. Transmitted mean photon number ($\mu_{rx}$) = 0.4
2. Error without signal ($E_{o}$) = 0.5
3. Dark count ($Y_o$) = 5.8 x $10^{-6}$
4. Error in detector ($E_{det}$) = 0.03

Depending on the type of location, the Estimated Zenith Transmission Coefficient ($T_o$) values vary. Here are the estimated $T_o$ values for different regions:

| Region         | Estimated Zenith Transmission Coefficient ($T_o$ Value) |
| -------------- | --------------------------------------------------------- |
| Metropolitan City | 0.6 to 0.8 |
| Outskirts of Metropolitan City | 0.7 to 0.9 |
| Desert | 0.8 to 0.95 |

These values and our simulator can help in better understanding and planning of quantum communication via satellites.
