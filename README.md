<!-- FILE VERSION: 1.1 | README publicznego repo jpnavera/allegro-api-apps (strona informacyjna aplikacji Allegro) | updated: 2026-10-19 | 1.1: precyzyjny opis cen w Cortex (kampanie) -->

# Aplikacje Allegro REST API firmy Navera

Navera Sp. z o.o., ul. Domaniewska 47/10, 02-672 Warszawa
KRS 0000461469, NIP 5213650256, REGON 146679524

Ta strona opisuje dwie aplikacje korzystające z Allegro REST API. Obie są
wewnętrznym oprogramowaniem firmy Navera i działają wyłącznie na koncie
sprzedawcy należącym do firmy Navera. Nie są udostępniane innym
użytkownikom Allegro ani firmom trzecim.

## Allegro Navi MCP

Nagłówek User-Agent: AllegroNaviMCP/<wersja> (+https://github.com/jpnavera/allegro-api-apps)

Cel: obsługa klientów i realizacja zamówień na własnym koncie sprzedawcy:
odczyt i odpowiedzi w Centrum wiadomości oraz w Dyskusjach i reklamacjach,
obsługa zamówień, tworzenie przesyłek Wysyłam z Allegro, zwroty, oceny,
raporty rozliczeń pobraniowych. Operacje finansowe (zwroty płatności,
decyzje w reklamacjach) zatwierdza pracownik firmy.

## Allegro Cortex MCP

Nagłówek User-Agent: AllegroCortexMCP/<wersja> (+https://github.com/jpnavera/allegro-api-apps)

Cel: zarządzanie promocjami, kampaniami i treścią ofert oraz raportowanie
sprzedaży i kosztów na własnym koncie sprzedawcy. Aplikacja nie zmienia
cen bazowych ani stanów magazynowych ofert (prowadzi je system sklepu
firmy); ceny promocyjne i liczbę sztuk podaje wyłącznie w zgłoszeniach
do kampanii i rabatów Allegro.

## Zasady

- Autoryzacja wyłącznie przez OAuth 2.0 Allegro; aplikacje nie przechowują
  loginów ani haseł.
- Dane Allegro są przetwarzane tylko na potrzeby obsługi własnej sprzedaży
  firmy Navera, w infrastrukturze firmy (Unia Europejska).
- Aplikacje przestrzegają limitów zapytań i Regulaminu REST API Allegro.

## Kontakt w sprawie aplikacji

biuro@navera.pl
