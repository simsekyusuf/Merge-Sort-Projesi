# Merge-Sort-Projesi
Proje 2
[16,21,11,8,12,22] -> Merge Sort

1)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.


1) :
                                                             [16, 21, 11, 8, 12, 22] - Başlangıç (LİSTENİN ELEMANLARI TEK KALINCAYA KADAR İKİYE BÖLEREK İŞLEM YAPIYORUZ)
                                                [16,21,11]                              [8,12,22]
                                           [16]            [21,11]                 [8]           [12,22]
                                     [16]             [21]        [11]         [8]           [12]        [22] ( TEK KALINCA SOLDAN BAŞLAYARAK KÜÇÜKTEN BÜYÜĞE SIRALANIR)
                                            [16]           [11,21]                    [8]         [12,22]
                                                 [11,16,21]                              [8,12,22]
                                                                 [8,11,12,16,21,22]

                             Sonuç olarak ortaya çıkan dizimiz: [8, 11, 12, 16, 21, 8, 12, 22]

2):            n
              n/2     şeklinde devam ettiği için  n=2^x   x = logn
              n/4                                      Big O = nlogn
