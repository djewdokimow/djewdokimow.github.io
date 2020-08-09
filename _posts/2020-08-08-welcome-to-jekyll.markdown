---
layout: post
title:  "Huawei Mobile Services"
date:   2020-08-09 20:00:00 +0200
categories: Android
---
Najnowsze telefony Huawei (Huawei P40 i P40 Pro, seria Mate 30, Mate Xs oraz Honor 30) nie mają dostępu do Sklepu Play do Usług Google Play. Oznacza to mniej więcej tyle, że jeśli stworzyłeś aplikację na system Android i wrzuciłeś ją tylko do Sklepu Play, to użytkownicy najnowszych telefonów Huawei nie będą ich mogli pobrać ze Sklepu Play, bo nie będą go mieli na swoim telefonie. Specjalnie dla nich trzeba teraz aplikację wrzucać do Huawei App Gallery, jednak bardzo możliwe, że wrzucenie tego samego pliku do obu sklepów nie rozwiąże całkowicie problemu. Jeśli masz w swojej aplikacji którąkolwiek funkcjonalności:
- mapy
- pobieranie lokalizacji
- geofencing
- komunikaty push
- app linki
- logowanie kontem
- reklamy
- analitykę
- skanowanie kodów kreskowych i QR
- zakupy w aplikacji
- platność kartą
- instant app
- zapis danych do chmury

i za dostarczenie jej odpowiada biblioteka Google Play Services, to możesz być pewien, że nie będą one działać na najnowszych telefonach Huawei.

Należy się spodziewać próśb od klientów - a najlepiej wycenić narzut czasowy i samemu im to zaproponować - o dostosowanie aplikacji do działania na smartfonach Huawei. Przekonanie ich do realizacji nie powinno być trudne. Jeśli masz w swoim projekcie podpiętą analitykę, jesteś w stanie bardzo szybko sprawdzić, jaki udział użytkowników aplikacji stanowili do tej pory posiadacze telefonów marki Huawei. Jeśli w twojej aplikacji można coś kupić, można przefiltrować w panelu Firebase, ile pieniędzy wydali ci użytkownicy. O ile klient nie będzie musiał zapłacić za rozbudowę więcej niż może zarobić, najprawdopodobniej się na nią zgodzi. Możliwe, że w najbliższym czasie nastąpi odwrót użytkowników od Huawei z powodu braku dostępności aplikacji, ale póki co nic na to nie wskazuje. Firma odnotowała w tym roku spadek liczby sprzedanych urządzeń, jednak procentowy udział na rynku się nie zmienił. Takie spadki odnotował właściwie każdy producent smartfonów i są one spowodowane rececją światowej gospodarki. Huawei ciągle pozostaje drugą po Samsungu marką smartfonów z Androidem. Dbania o posiadaczy jego urządzeń będzie wiązało się z większymi nakładami czasowymi niż ze wspierania urządzeń sprzed pięciu lat, jednak korzyści też będą większe.

Jak się do tego zabrać

Przemyślenia

W ostatnim czasie zajmowałem się rozbudową dwóch aplikacji, by na urządzeniach Huawei aplikacje odbierały powiadomienia push, można było logować się kontem Huawei ID, dało się nimi odczytywać kody QR i aby działało raportowanie analityki. Po zakończeniu prac nad 

Problemy

Jak to wycenić