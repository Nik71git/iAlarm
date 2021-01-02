# iAlarm
 
**CASASICURA REL 2.0** 
questo è il flusso completo con i sensori e gli attributi "lowbat" e "fault".

importare il flusso in Node Red e poi personalizzare i dati relativi alla centrale, al broker MQTT ed al server Home Assistant; il flusso pubblica solamente al cambio di stato di uno dei valori tra "open", "lowbat" e "fault".

**CASASICURA LITE REL 1.0**
questo è il flusso con i sensori **PRIVI** degli attributi "lowbat" e "fault".

importare il flusso in Node Red e poi personalizzare i dati relativi alla centrale, al broker MQTT ed al server Home Assistant; il flusso pubblica solamente al cambio di stato del valore "open".

*Occorre avere già integrato Node Red da HACS ed avere installato l'addon Node Red in Home Assistant*
