# SO_Projekti1
# Projekti 1: Sistemi i shpërndarë duke përdorur Inter Process Communications (IPC), Threads dhe Sinkronizimi

Ky projekt është një sistem i shpërndarë i zhvilluar në gjuhën C në Linux, duke përdorur Inter Process Communications (IPC), thread-et dhe sinkronizimin.

## Përshkrimi i projektit

Projekti përbëhet nga një server që mundëson komunikimin me shumë klientë në të njëjtën kohë. Klientët mund të komunikojnë me serverin përmes tubave, kalimit të mesazheve ose përdorimit të kujtimit të përbashkët.


## Përdorimi

1. Ekzekutoni serverin: `./server`
2. Ekzekutoni klientin: `./client`
3. Pasi ekzekutoni klientin, ju do të jeni në gjendje të dërgoni kërkesa dhe të merrni përgjigje nga serveri.

## Implementimi

Projekti përdor një strukturë të ndarë në server dhe klient për të siguruar ndarjen dhe sinkronizimin e burimeve. Serveri përdor thread-et për të trajtuar kërkesat e klientëve në mënyrë paralele. Serveri gjithashtu aplikon mekanizma të sinkronizimit si mutex dhe semaforë për të parandaluar konfliktet ndërmjet thread-eve.

## Shënime të rëndësishme

- Numri maksimal i klientëve që mund të lidhen me serverin është i konfiguruar në kodin e serverit dhe mund të ndryshohet sipas nevojës.

## Përmbajtje e projektin

- **server.c**: Kod burimor i programit të serverit.
- **client.c**: Kod burimor i programit të klientit.
- **README.md**: Skedari aktual që përmban udhëzimet për projektin.

## Kontribuesit

- Erand Kurtaliqi
- Endrit Abazi
- Era Maliqi
- Elda Reqica



















