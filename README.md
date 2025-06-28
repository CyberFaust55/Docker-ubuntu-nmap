Opis ćwiczenia: Docker + Ubuntu + Nmap

1. Uruchomiłem kontener z Ubuntu w Docker Desktop.
2. Wszedłem do terminala kontenera jako root (#) i zainstalowałem nmap przez apt.
3. Sprawdziłem wersję nmap i upewniłem się, że działa.
4. Zapisałem stan kontenera (docker commit) jako obraz lokalny o nazwie: adam55/ubuntu-nmap
5. W GUI sprawdziłem obraz i przeanalizowałem podatności (Docker Scout).
6. Widzę teraz ten obraz w zakładce 'Images' i mogę go użyć w przyszłości.

Użyte polecenia (m.in.):
- docker ps -a
- docker commit happy_babbage adam55/ubuntu-nmap
- apt install nmap
- nmap -v

Cel: przygotować gotowe środowisko testowe z nmap w kontenerze.
