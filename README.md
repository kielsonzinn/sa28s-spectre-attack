# Link's

- https://seedsecuritylabs.org/Labs_20.04/System/Spectre_Attack/
- https://www.youtube.com/watch?v=_zIHNVpXZGI

## STEP 01

gcc -march=native -o CacheTime CacheTime.c
./CacheTime

## STEP 02

gcc -march=native -o FlushReload FlushReload.c
./FlushReload

## STEP 03

gcc -march=native -o SpectreExperiment SpectreExperiment.c
./SpectreExperiment

## STEP 04

gcc -march=native -o SpectreAttack SpectreAttack.c
./SpectreAttack

## STEP 05

gcc -march=native -o SpectreAttackImproved SpectreAttackImproved.c
./SpectreAttackImproved

## STEP 06

gcc -march=native -o SpectreAttackCompleted SpectreAttackCompleted.c
./SpectreAttackCompleted
