# Zestawić sieć neuronową opartą tylko na warstwach fully connected w Pytorch i przeprowadzić trening oraz test na zbiorze CIFAR10


Autorzy: Jakub Prażuch, Aleksander Bryl

### Wyniki
Uzyskana dokładność **64%** przy 100 epokach na 4 warstwach **fully connected**. Optimizer **Adam** z **StepLR** schedulerem. Sporo transformacji spowoliniło przeuczenie. Lepsze wyniki można byłoby osiągnąć dodając warstwy konwolucyjne.

![Best scores png](Best%20scores%20~64%25.png)