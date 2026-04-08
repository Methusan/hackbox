# Hackbox 🔍

Script Bash d'automatisation des premières étapes d'un audit réseau.

## Objectif

Gagner du temps sur la phase de reconnaissance lors de tests 
d'intrusion en automatisant les commandes de base.

## Fonctionnement

Lancé depuis Kali Linux, le script exécute automatiquement :

1. **Scan Nmap** — découverte des hôtes et des ports ouverts
2. **Énumération des services** — identification des services sur chaque port
3. **Scan de vulnérabilités** — détection des failles connues
4. **Rapport** — synthèse des informations réseau collectées

## Utilisation

```bash
git clone https://github.com/Methusan/hackbox
cd hackbox
chmod +x hackbox.sh
./hackbox.sh 
```

## ⚠️ Avertissement

Cet outil est destiné uniquement à des fins éducatives et à des tests 
sur des environnements pour lesquels vous avez une autorisation explicite. 
Toute utilisation non autorisée est illégale.

## Compétences mobilisées

`Bash` `Kali Linux` `Nmap` `Pentest` `Reconnaissance réseau` `Cybersécurité`
