# Media Setup Ansible

## BELANGRIJK

Dit script is alleen getest op debian 13 (trixie)

## Benodigdheden

- python (voor ansible)
- ansible-playbook

```
python3 -m pip install --user ansible
```

## Configuratie
Pas in de volgende file de variables aan naar jou voorkeur.
`inventory/group_vars/all.yml`

Pas in de volgende file het ip adres van je device aan.
`inventory/hosts`

## Uitvoeren van het script
```
./run_ansible.sh
```

## Applications

### bazarr
Port: `6767`

### dockge
Port: `5001`

### immich
Port: `2283`

### jackett
Port: `9117`

### jellyfin
Port: `8096`

### radarr
Port: `7878`

### sonarr
Port: `8989`

### transmission
Port: `9091`
