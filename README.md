# WSB_Projekt_Programowanie_Zaawansowane
Projekt z programowania zaawansowanego 

Projekt zaliczeniowy polega na stworzeniu strony internetowej. Tematyka jest dowolna, ale musi być wybrana w taki sposób, by spełnić wszystkie wymagania podane niżej. Zatem tematyka, która naturalnie pomija niektóre funkcjonalności (np. strony na których nie ma sensu tworzenie kont użytkowników), nie jest akceptowalna.

**Wymagania funkcjonalne:**

1. projekt musi posiadać bazę danych, łączyć się z nią, pobierać z niej dane i wstawiać do niej dane; technologia dowolna;
2. projekt musi posiadać możliwość rejestracji kont użytkowników, logowania i wylogowania;
3. projekt musi posiadać podstrony dostępne publicznie i podstrony tylko dla użytkowników;
4. projekt musi uwzględniać indywidualną interakcję użytkownika (np. przesłanie formularza, z którego dane będą przechowywane w bazie i przypisane będą do tegoż użytkownika).
5. Projekt musi być napisany w języku C#.


**#Projekt Umawianie Wizyt Stomatologicznych**

Projekt Umawianie Wizyt Stomatologicznych jest stroną internetową umożliwiającą użytkownikom umawianie wizyt u stomatologa. Projekt został stworzony w ramach zadania zaliczeniowego.

**Wymagania**

Aby uruchomić projekt lokalnie, wymagane są następujące narzędzia:
1. Visual Studio (wersja 2019 lub nowsza) lub inny edytor kodu
2. .NET Core SDK (wersja 3.1 lub nowsza)
3. Baza danych (np. SQL Server, MySQL)

**Instrukcje instalacji**

Sklonuj repozytorium na swoje lokalne środowisko:
**git clone https://github.com/twoj-repozytorium.git**
Otwórz projekt w wybranym edytorze kodu (np. Visual Studio).
Skonfiguruj połączenie do bazy danych w pliku appsettings.json.
Uruchom migracje, aby zaktualizować bazę danych:
**dotnet ef database update**
Uruchom projekt:
**dotnet run**
Otwórz przeglądarkę internetową i przejdź do adresu http://localhost:5000, aby zobaczyć stronę główną projektu.

**Dokumentacja API**

Projekt udostępnia API, które umożliwia komunikację z aplikacją. Dokumentacja API jest dostępna pod adresem http://localhost:5000/swagger, po uruchomieniu projektu.


**Autorzy**

Przemysław Wierzbicki

Mikołaj Bielak
