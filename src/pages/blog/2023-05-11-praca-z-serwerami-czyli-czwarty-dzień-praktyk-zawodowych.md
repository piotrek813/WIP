---
layout: "@layouts/BlogLayout.astro"
title: Praca z serwerami, czyli czwarty dzień praktyk zawodowych
excerpt: Czwarty dzień praktyk zawodowych w firmie EIP był dniem serwerowym.
  Rozpoczął się częścią teoretyczną, w której Pan Kucharczyk zapoznał nas z
  fizyczną strukturą serwerów, jej funkcjonalnością i zabezpieczającą
  redundantnością.
date: 2023-05-11T20:20:52.813Z
image: /images/img_7239.jpg
category: Praktyki
author: Aleksander Czarnowski
tags:
  - praktyki, wiśniowa, eip
---
Czwarty dzień praktyk zawodowych w firmie EIP był dniem serwerowym. Rozpoczął się częścią teoretyczną, w której Pan Kucharczyk zapoznał nas z fizyczną strukturą serwerów, jej funkcjonalnością i zabezpieczającą redundantnością np. dwoma zasilaczami lub rozbudowanym systemem aktywnego chłodzenia, którego szarganie powietrza i nerwów było z nami obecne przez resztę dnia.

Następna godzina upłynęła nam na poszerzaniu zakresu wiedzy na temat boot managerów, które umożliwiają instalację wielu systemów operacyjnych na jednej maszynie i miały okazać się przydatne w kolejnym zadaniu. Wśród kandydatów wytypowanych do późniejszej eksploatacji znalazły się EasyBCD, Grub2Win oraz rEFine.

Po grupowej burzy mózgów, w której zdecydowaliśmy, że Grub2Win będzie najlepszym wyborem, przystąpiliśmy do konfiguracji hardware. Wymieniliśmy kości pamięci RAM, po czym zdiagnozowaliśmy działanie i wymieniliśmy uszkodzone lub stare dyski twarde.

Ze sprzętem w gotowości, mogliśmy zabrać się za ustawianie stosownych macierzy dyskowych RAID. Projekt składał się z ośmiu dysków. Dwa pierwsze miały zawierać systemy operacyjne - dla zwiększonego bezpieczeństwa postanowiliśmy połączyć je w RAID 1 (disk mirroring). Reszta dysków była przeznaczona na dane. W celu uodpornienia ich na straty postanowiliśmy zastosować dla nich macierz RAID 5 z jednym dyskiem zapasowym (spare).

Reszta dnia upłynęła na instalacji systemów operacyjnych na przygotowanych przez nas serwerach m.in. Windows 10, Windows Server i Ubuntu.