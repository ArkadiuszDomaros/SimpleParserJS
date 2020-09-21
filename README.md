<p>Program stworzony na potrzeby przedmiotu na studiach.</p>
<p></p>
<p>Polecenie zadania:</p>
<p></p>
<p>Napisać skrypt, który zwykły tekst przetworzy na kod html, według następujących schematów:</p>
<p>Każda linia bez specjalnej interpretacji tworzy osobny paragraf (znacznik < p>)</p>
<p>Cudzysłowy proste “ zamieniamy na znaczniki cytatu - w zależności od parzystości otwarcie <q> lub zamknięcie < /q>. Opcjonalnie naprzemienne cudzysłowy proste podwójne “ i pojedyncze ‘ możemy zamieniać na zagnieżdżone znaczniki cytatu.</p>
<p>Znak ^ ma oznaczać otwarcie < sup> a znak _ otwarcie < sub>. Oba znaczniki zamykamy przy kolejnej spacji lub innym białym znaku.</p>
<p>Linie rozpoczynające się znakiem > mają być zawartością < blockquote>. Powielone znaki mają określać stopień zagnieżdżenia cytatu blokowego. Kolejne linie cytatu blokowego, to paragrafy zagnieżdżone wewnątrz niego.</p>
<p>Linie rozpoczynające się numerem i kropką 1. mają tworzyć element < li> listy numerowanej < ol>. Lista ma być utworzona wraz z pierwszym numerem i zamknięta, gdy natrafimy na linię bez numeracji.</p>
<p>Przykład 1:</p>
<p>Ania ma 3 koty:</p>
<p>1. Czarny kot Bruno</p>
<p>2. Rudy kot Leon</p>
<p>3. Biała kotka Atena</p>
<p>Atena często miaucze “miau”, Leon dużo mruczy “purrr”, a Bruno to w sumie głównie śpi i mało go słychać.</p>
<p>Wyjście:</p>
<p>< p>Ania ma 3 koty:</ p></p>
<p>< ul></p>
<p>< li>Czarny kot Bruno< /li></p>
<p>< li>Rudy kot Leon< /li></p>
<p>< li>Biała kotka Atena< /li></p>
<p>< /ul></p>
<p>< p>Atena często miaucze < q>miau< /q>, Leon dużo mruczy < q>purrr< /q>, a Bruno to w sumie głównie śpi i mało go słychać.< /p></p>
<p></p>	
<p>Przykład 2:</>
	<p>>>>Dlaczego Słowacki wzbudza w nas zachwyt i miłość? Dlatego, panowie, że Słowacki wielkim poetą był!</p>
	<p>>>Poezja Słowackiego nikogo nie zachwyca</p>
	<p>>Jak to nie zachwyca Gałkiewicza, jeśli tysiąc razy tłumaczyłem Gałkiewiczowi, że go zachwyca.</p>
<p>Wyjście:</p>
<p>< blockquote></p>
<p>< blockquote></p>
<p>< blockquote>
<p>< p>Dlaczego Słowacki wzbudza w nas zachwyt i miłość? Dlatego, panowie, że Słowacki wielkim poetą był!< /p></p>
<p>< /blockquote></p>
<p>< p>Poezja Słowackiego nikogo nie zachwyca</ p></p>
<p>< /blockquote></p>
<p>< p>Jak to nie zachwyca Gałkiewicza, jeśli tysiąc razy tłumaczyłem Gałkiewiczowi, że go zachwyca.< /p></p>
<p>< /blockquote></p>

