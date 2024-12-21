Tubes Analisis Kompleksitas Algoritma
Perbandingan algoritma iteratif dan rekursif pada reverse string
dibuat oleh kelompok dengan beranggotakan 2 orang:
- Muhammad Irgiansyah(103012300039)
- Dandy Fadhilla(103012300180)

Code reverse string secara iteratif
procedure reverseStringIterative(str : string) 
kamus
    i : int
algoritma
    for i = length(str) downto 1 do
        output(str[i])
    endfor
endprocedure

---------------------------------------------------------------------

Code reverse string secara rekursif
procedure reverseStringRecursive(str : string, idx : int)
kamus 
algoritma
    if idx < 0 then
        return
    else 
        output (str[idx])
        idx = idx - 1
        reverseStringRecursive(str, idx)
    endif
endprocedure
