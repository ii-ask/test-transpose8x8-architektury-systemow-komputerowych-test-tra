[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zwkXWVlg)
Transpozycja macierzy bitowej 8x8
===

W pliku `transpose.s` zaprogramuj w asemblerze `x86-64` procedurę o sygnaturze
`uint64_t transpose8x8(uint64_t)`, która traktuje podane 64-bitowe słowo maszynowe 
jako dwuwymiarową macierz bitów o wymiarach 8x8 (gdzie najmłodszy bajt to pierwszy 
wiersz, kolejny bajt to drugi wiersz itd.). Funkcja ma dokonać transpozycji tej 
macierzy, czyli zamienić wiersze z kolumnami (odbić bity względem głównej przekątnej), 
i zwrócić wynikową 64-bitową liczbę.

Rozwiązanie ma działać w czasie `O(log n)`, gdzie `n` jest długością słowa maszynowego.

### Ważne:

1. Można używać wyłącznie instrukcji poznanych na wykładzie i ćwiczeniach.
2. Użycie rozszerzeń BMI2 (instrukcje takie jak `pdep`, `pext`) jest niedozwolone!
3. Modyfikowanie innych plików niż `transpose.s` jest niedozwolone!
4. Twoje rozwiązanie nie powinno być dłuższe niż 50 instrukcji.
5. Pełną liczbę punktów można uzyskać wyłącznie za rozwiązanie, które nie 
używa instrukcji skoków (branch-free). Dokładniejsze informacje można znaleźć w pliku 
`.github/classroom/autograding.json`.
6. Za rozwiązanie spełniające powyższe oraz dodatkowe wymogi określone 
w pliku Makefile, można uzyskać punkt bonusowy (nie jest on widoczny na 
Github).

### Pamiętaj:

1. Podpisz się w treści rozwiązania.
2. Nie zamykaj _Pull Request_ o nazwie _Feedback_!
3. W zakładce _zmienione pliki_ (ang. _changed files_) _Pull Request_ o nazwie
   _Feedback_ ma być widać wyłącznie treść Twojego rozwiązania!
