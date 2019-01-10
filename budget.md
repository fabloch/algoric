# Budget

## Coûts d’exploitation
Les prix de Amazon Computing sont de 0.05 USD par vCPU par heure. (https://aws.amazon.com/fr/ec2/pricing/on-demand/) pour du Linux, le double pour du Windows.

Attention par contre, ce sont des générations Broadwell/Skylake, donc prendre un facteur 1.5 si on propose du Sandy/Ivy (AVX -> AVX2).

En supposant que l’on dispose de CPUs Sandy/Ivy, disons 16 vCPU par lames de 600W, à raison de 0.15€ le kWh en moyenne, cela donne 0.006€ en coût d’exploitation par vCPU.

En ajoutant l’infrastructure (Ethernet, Infiniband, Stockage), disons x 1.5.

On peut donc afficher des prix similaires, en dégageant une marge.

Bien entendu, cette étude demanderait à être affinée.


coût du recyclage

- maintenance ( pièces ): provisions à prévoir;
- coût d’administration ( Benoit pour commencer, mais quid si il arrête ou lève le pied pour X raison).
