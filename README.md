# Filius-Router

## Obbiettivo:
### Lo scopo di questo compito era correggere una rete, configurata male, in modo da riuscire a fare comunicare i pc di una sottorete con i pc dell'altra sottorete dovendo utilizzare anche protocollo DHCP

## Risoluzione:

### Inanzitutto abbiamo configurato il router assegnando i giusti ip alle 2 porte
### ![router](/router/ip.png)

### In seguito abbiamo configurato i pc delle reti assegnando a 1 dei due ip e gateway e all'altro assegnavamo l'ip tramite DHCP:
### ![pc](/router/pc.png)

### Qua assegnamo gateway e DNS Server in modo da far funzionare il nostro assegnamento tramite DHCP
### ![dhcp](/router/dhcp.png)

### Infiine eseguendo un ping da una un pc di una rete al pc dell'altra rete possiamo notare che riescono a comunicare e quindi i pacchetti vengono inviati con successo senza errori:
### ![ping](/router/ping.png)
