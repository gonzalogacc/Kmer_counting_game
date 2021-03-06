# Kmer_counting_game

Original genome
```
TTTATAGACCTTAACGTGGAAAAGGTCACCCGCTCGACTGCTGTGGACAAGGTAGTCGTGAACATGAATGACCTTTTCCACTGTCTTTGGGAACCACAG
```

Sequence 5-mers

```
1, TTTAT, ATAAA
2, TTATA, TATAA
3, TATAG, CTATA
4, ATAGA, TCTAT
5, TAGAC, GTCTA
6, AGACC, GGTCT
7, GACCT, AGGTC
8, ACCTT, AAGGT
9, CCTTA, TAAGG
10, CTTAA, TTAAG
11, TTAAC, GTTAA
12, TAACG, CGTTA
13, AACGT, ACGTT
14, ACGTG, CACGT
15, CGTGG, CCACG
16, GTGGA, TCCAC
17, TGGAA, TTCCA
18, GGAAA, TTTCC
19, GAAAA, TTTTC
20, AAAAG, CTTTT
21, AAAGG, CCTTT
22, AAGGT, ACCTT
23, AGGTC, GACCT
24, GGTCA, TGACC
25, GTCAC, GTGAC
26, TCACC, GGTGA
27, CACCC, GGGTG
28, ACCCG, CGGGT
29, CCCGC, GCGGG
30, CCGCT, AGCGG
31, CGCTC, GAGCG
32, GCTCG, CGAGC
33, CTCGA, TCGAG
34, TCGAC, GTCGA
35, CGACT, AGTCG
36, GACTG, CAGTC
37, ACTGC, GCAGT
38, CTGCT, AGCAG
39, TGCTG, CAGCA
40, GCTGT, ACAGC
41, CTGTG, CACAG
42, TGTGG, CCACA
43, GTGGA, TCCAC
44, TGGAC, GTCCA
45, GGACA, TGTCC
46, GACAA, TTGTC
47, ACAAG, CTTGT
48, CAAGG, CCTTG
49, AAGGT, ACCTT
50, AGGTA, TACCT
51, GGTAG, CTACC
52, GTAGT, ACTAC
53, TAGTC, GACTA
54, AGTCG, CGACT
55, GTCGT, ACGAC
56, TCGTG, CACGA
57, CGTGA, TCACG
58, GTGAA, TTCAC
59, TGAAC, GTTCA
60, GAACA, TGTTC
61, AACAT, ATGTT
62, ACATG, CATGT
63, CATGA, TCATG
64, ATGAA, TTCAT
65, TGAAT, ATTCA
66, GAATG, CATTC
67, AATGA, TCATT
68, ATGAC, GTCAT
69, TGACC, GGTCA
70, GACCT, AGGTC
71, ACCTT, AAGGT
72, CCTTT, AAAGG
73, CTTTT, AAAAG
74, TTTTC, GAAAA
75, TTTCC, GGAAA
76, TTCCA, TGGAA
77, TCCAC, GTGGA
78, CCACT, AGTGG
79, CACTG, CAGTG
80, ACTGT, ACAGT
81, CTGTC, GACAG
82, TGTCT, AGACA
83, GTCTT, AAGAC
84, TCTTT, AAAGA
85, CTTTG, CAAAG
86, TTTGG, CCAAA
87, TTGGG, CCCAA
88, TGGGA, TCCCA
89, GGGAA, TTCCC
90, GGAAC, GTTCC
91, GAACC, GGTTC
92, AACCA, TGGTT
93, ACCAC, GTGGT
94, CCACA, TGTGG
95, CACAG, CTGTG
```

Sequence 7-mers

```
1, TTTATAG, CTATAAA
2, TTATAGA, TCTATAA
3, TATAGAC, GTCTATA
4, ATAGACC, GGTCTAT
5, TAGACCT, AGGTCTA
6, AGACCTT, AAGGTCT
7, GACCTTA, TAAGGTC
8, ACCTTAA, TTAAGGT
9, CCTTAAC, GTTAAGG
10, CTTAACG, CGTTAAG
11, TTAACGT, ACGTTAA
12, TAACGTG, CACGTTA
13, AACGTGG, CCACGTT
14, ACGTGGA, TCCACGT
15, CGTGGAA, TTCCACG
16, GTGGAAA, TTTCCAC
17, TGGAAAA, TTTTCCA
18, GGAAAAG, CTTTTCC
19, GAAAAGG, CCTTTTC
20, AAAAGGT, ACCTTTT
21, AAAGGTC, GACCTTT
22, AAGGTCA, TGACCTT
23, AGGTCAC, GTGACCT
24, GGTCACC, GGTGACC
25, GTCACCC, GGGTGAC
26, TCACCCG, CGGGTGA
27, CACCCGC, GCGGGTG
28, ACCCGCT, AGCGGGT
29, CCCGCTC, GAGCGGG
30, CCGCTCG, CGAGCGG
31, CGCTCGA, TCGAGCG
32, GCTCGAC, GTCGAGC
33, CTCGACT, AGTCGAG
34, TCGACTG, CAGTCGA
35, CGACTGC, GCAGTCG
36, GACTGCT, AGCAGTC
37, ACTGCTG, CAGCAGT
38, CTGCTGT, ACAGCAG
39, TGCTGTG, CACAGCA
40, GCTGTGG, CCACAGC
41, CTGTGGA, TCCACAG
42, TGTGGAC, GTCCACA
43, GTGGACA, TGTCCAC
44, TGGACAA, TTGTCCA
45, GGACAAG, CTTGTCC
46, GACAAGG, CCTTGTC
47, ACAAGGT, ACCTTGT
48, CAAGGTA, TACCTTG
49, AAGGTAG, CTACCTT
50, AGGTAGT, ACTACCT
51, GGTAGTC, GACTACC
52, GTAGTCG, CGACTAC
53, TAGTCGT, ACGACTA
54, AGTCGTG, CACGACT
55, GTCGTGA, TCACGAC
56, TCGTGAA, TTCACGA
57, CGTGAAC, GTTCACG
58, GTGAACA, TGTTCAC
59, TGAACAT, ATGTTCA
60, GAACATG, CATGTTC
61, AACATGA, TCATGTT
62, ACATGAA, TTCATGT
63, CATGAAT, ATTCATG
64, ATGAATG, CATTCAT
65, TGAATGA, TCATTCA
66, GAATGAC, GTCATTC
67, AATGACC, GGTCATT
68, ATGACCT, AGGTCAT
69, TGACCTT, AAGGTCA
70, GACCTTT, AAAGGTC
71, ACCTTTT, AAAAGGT
72, CCTTTTC, GAAAAGG
73, CTTTTCC, GGAAAAG
74, TTTTCCA, TGGAAAA
75, TTTCCAC, GTGGAAA
76, TTCCACT, AGTGGAA
77, TCCACTG, CAGTGGA
78, CCACTGT, ACAGTGG
79, CACTGTC, GACAGTG
80, ACTGTCT, AGACAGT
81, CTGTCTT, AAGACAG
82, TGTCTTT, AAAGACA
83, GTCTTTG, CAAAGAC
84, TCTTTGG, CCAAAGA
85, CTTTGGG, CCCAAAG
86, TTTGGGA, TCCCAAA
87, TTGGGAA, TTCCCAA
88, TGGGAAC, GTTCCCA
89, GGGAACC, GGTTCCC
90, GGAACCA, TGGTTCC
91, GAACCAC, GTGGTTC
92, AACCACA, TGTGGTT
93, ACCACAG, CTGTGGT
```

