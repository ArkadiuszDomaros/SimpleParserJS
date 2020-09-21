Program stworzony na potrzeby przedmiotu na studiach.

Polecenie zadania:

<blockquote>

Napisać skrypt, który zwykły tekst przetworzy na kod html, według następujących schematów:
Każda linia bez specjalnej interpretacji tworzy osobny paragraf (znacznik <p>)
Cudzysłowy proste “ zamieniamy na znaczniki cytatu - w zależności od parzystości otwarcie <q> lub zamknięcie </q>. Opcjonalnie naprzemienne cudzysłowy proste podwójne “ i pojedyncze ‘ możemy zamieniać na zagnieżdżone znaczniki cytatu.
Znak ^ ma oznaczać otwarcie <sup> a znak _ otwarcie <sub>. Oba znaczniki zamykamy przy kolejnej spacji lub innym białym znaku.
Linie rozpoczynające się znakiem > mają być zawartością <blockquote>. Powielone znaki mają określać stopień zagnieżdżenia cytatu blokowego. Kolejne linie cytatu blokowego, to paragrafy zagnieżdżone wewnątrz niego.
Linie rozpoczynające się numerem i kropką 1. mają tworzyć element <li> listy numerowanej <ol>. Lista ma być utworzona wraz z pierwszym numerem i zamknięta, gdy natrafimy na linię bez numeracji.
Przykład 1:
Ania ma 3 koty:
1. Czarny kot Bruno
2. Rudy kot Leon
3. Biała kotka Atena
Atena często miaucze “miau”, Leon dużo mruczy “purrr”, a Bruno to w sumie głównie śpi i mało go słychać.
Wyjście:
<p>Ania ma 3 koty:</p>
<ul>
<li>Czarny kot Bruno</li>
<li>Rudy kot Leon</li>
<li>Biała kotka Atena</li>
</ul>
<p>Atena często miaucze <q>miau</q>, Leon dużo mruczy <q>purrr</q>, a Bruno to w sumie głównie śpi i mało go słychać.</p>
Przykład 2:
	>>>Dlaczego Słowacki wzbudza w nas zachwyt i miłość? Dlatego, panowie, że Słowacki wielkim poetą był!
	>>Poezja Słowackiego nikogo nie zachwyca
	>Jak to nie zachwyca Gałkiewicza, jeśli tysiąc razy tłumaczyłem Gałkiewiczowi, że go zachwyca.
Wyjście:
<blockquote>
<blockquote>
<blockquote>
<p>Dlaczego Słowacki wzbudza w nas zachwyt i miłość? Dlatego, panowie, że Słowacki wielkim poetą był!</p>
</blockquote>
<p>Poezja Słowackiego nikogo nie zachwyca<p>
</blockquote>
<p>Jak to nie zachwyca Gałkiewicza, jeśli tysiąc razy tłumaczyłem Gałkiewiczowi, że go zachwyca.<p>
</blockquote>
	
</blockquote>
