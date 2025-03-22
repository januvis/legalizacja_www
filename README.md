# legalizacja_www
nowy system www
System do obsługi wysyłkowej legalizacji małych (do 18 litrów) butli ciśneniowych. Musi być wielojęzyczny (na początek j.polski + j.angielski) - później rozbudujemy o kolejne (niemiecki, czeski, słowacki)
Usługa polega na:
1. odebraniu przez kuriera przygotowanej przez Klienta butli.
2. dostarczeniu butli do naszego Zakładu Legalizacji (adres: ul. Wolności 98A; 43-229 Rudołtowice k. Pszczyny; Polska; tel: +48 885 155 303; e-mail: legalizacja@remgaz.com.pl; email supportu: support@remgaz.com.pl)
3. przygotowanie butli do legalizacji (rozpakowanie, naklejenie kodu paskowego - w celu identyfikacji butli, inspekcje zewnętrzna, wykręcenie zaworu, inspekcja wewnętrzna, ewentualne wyczyszczenie butli wewnątrz- jeśli stan butli tego wymaga (rdza) lub jeśli zlecone dodatkowo przez Klienta, nabicie nowych znaków legalizacyjnych (data w formacie: rok (4 cyfry) / miesiąc (2 cyfry) …spacja… rok (ważności badania) - w miejsce spacji nabija się indywidualny znak inspektora UDT lub TDT, poddanie butli wodnej próbie ciśnieniowej - na ciśnienie = 150% ciśnienia roboczego (np. dla butli o ciśnieniu roboczym PW200BAR ciśnienie próby PH300BAR), pasywacji chamicznej wewnętrznej powierzchni butli (na dodatkowe zlecenie Klienta), osuszeniu wnętrza butli, wkręcenie zaworu, malowanie butli (na dodatkowe zlecenie Klienta, przygotowaniu do wysyłki (pakowanie, etykiety zamówienie kuriera, przekazaniu kurierowi do wysyłki.
4. to wszystkie potencjalne kroki związane z wysyłkową legalizacją butli.
5. Systam musi zawierać:
   a. 3 logicznie spójne obszary robocze (Strona Główna, Strona Klienta (zalogowanego), Panel Admministratora (oraz jego okrojoną wersję - Panel Operatora)
   b. 3 podstawowe role userów: (Klient, Administrator, Operator)
6. Systam będzie obsługiwał typowe systemy płatności (Blik, Przelew elektroniczny, przekaz pocztowy, PayPal) a także musi być przygotowane na integrację z systemem Stripe
7. Wysyłki bedą realizowane za pomocą firmy kurierskiej lub systemu apaczka.pl poprzez integrację przez konkretne API.


Konfiguracja Systamu (pełna) będzie się odbywała z poziomu Administratora.

Opisy poszczególnych ról i sekcji w plikach:
admin.txt
klient.txt
operator.txt
