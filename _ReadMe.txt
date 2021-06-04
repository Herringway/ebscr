---------------------------------
EarthBound Script Source Recovery
Rich Whitehouse
2019-04-16
---------------------------------

All of these files were recovered from unreferenced disk sectors. The disk image in question has a believable-looking FAT and root directory, but for the files that do have directory entries, clusters often end up leading us to sectors which don't seem to belong and contain stale/incorrect data. Because the data present here isn't referenced at all, it's likely that it was intentionally deleted from the disk and the sectors were never reused.

I wrote a Noesis script to extract this data from the image directly. The data recovered was initially compressed and I was able to decompress it without issue, so it's reasonably safe to say these files survived fully intact.

There's a lot of inline Japanese, so view as Shift-JIS. See below for each file's stats.


E01ONET0.MSG - Size: 19067 / 69956 Offset: 802304 Time: 1995/3/24 : 22h55m44s
E01ONET1.MSG - Size: 18568 / 68998 Offset: 821371 Time: 1995/3/24 : 22h55m46s
E01ONET2.MSG - Size: 19523 / 71365 Offset: 839939 Time: 1995/3/24 : 22h55m48s
E02TWSN0.MSG - Size: 17540 / 63865 Offset: 859462 Time: 1995/3/25 : 22h54m6s
E02TWSN1.MSG - Size: 13750 / 50773 Offset: 877002 Time: 1995/3/24 : 22h55m50s
E02TWSN2.MSG - Size: 16832 / 57989 Offset: 890752 Time: 1995/3/24 : 22h55m52s
E03HAPPY.MSG - Size: 13722 / 53362 Offset: 907584 Time: 1995/3/24 : 22h55m52s
E04GRFD.MSG - Size: 4418 / 12309 Offset: 921306 Time: 1995/3/24 : 22h55m54s
E05THRK.MSG - Size: 17517 / 64125 Offset: 925724 Time: 1995/3/24 : 22h55m54s
E06WINS.MSG - Size: 22342 / 80179 Offset: 943241 Time: 1995/3/25 : 22h54m6s
E07GPFT.MSG - Size: 5054 / 17375 Offset: 965583 Time: 1995/3/24 : 22h55m56s
E08DOSEI.MSG - Size: 13833 / 48947 Offset: 970637 Time: 1995/3/25 : 22h54m8s
E09DSRT.MSG - Size: 21834 / 91904 Offset: 984470 Time: 1995/3/24 : 22h55m58s
E10FOUR0.MSG - Size: 21023 / 78484 Offset: 1006304 Time: 1995/3/25 : 22h54m8s
E10FOUR1.MSG - Size: 18046 / 65897 Offset: 1027327 Time: 1995/3/24 : 22h56m0s
E11SUMS.MSG - Size: 17178 / 61677 Offset: 1045373 Time: 1995/3/24 : 22h56m2s
E12RAMA.MSG - Size: 8251 / 26882 Offset: 1062551 Time: 1995/3/25 : 22h54m10s
E13SKRB.MSG - Size: 10674 / 37301 Offset: 1070802 Time: 1995/3/24 : 22h56m4s
E14MAKYO.MSG - Size: 6850 / 21789 Offset: 1081476 Time: 1995/3/25 : 23h4m12s
E15GUMI.MSG - Size: 8767 / 29289 Offset: 1088326 Time: 1995/3/24 : 22h56m4s
E16DKFD.MSG - Size: 6880 / 20221 Offset: 1097093 Time: 1995/3/24 : 22h56m6s
E17PAST.MSG - Size: 1354 / 3174 Offset: 1103973 Time: 1995/3/8 : 19h21m52s
E18MGKT.MSG - Size: 9539 / 36824 Offset: 1105327 Time: 1995/3/24 : 22h56m6s
E19MOON.MSG - Size: 8198 / 32898 Offset: 1114866 Time: 1995/3/23 : 12h7m56s
EBATTLE0.MSG - Size: 3032 / 12754 Offset: 1123064 Time: 1995/3/24 : 19h5m2s
EBATTLE1.MSG - Size: 2515 / 8610 Offset: 1126096 Time: 1995/3/25 : 22h54m10s
EBATTLE2.MSG - Size: 2647 / 10877 Offset: 1128611 Time: 1995/3/20 : 23h25m28s
EBATTLE3.MSG - Size: 2619 / 10754 Offset: 1131258 Time: 1995/3/24 : 21h19m30s
EBATTLE4.MSG - Size: 4071 / 13807 Offset: 1133877 Time: 1995/3/24 : 22h56m8s
EBATTLE5.MSG - Size: 3375 / 15492 Offset: 1137948 Time: 1995/3/25 : 23h4m14s
EBATTLE6.MSG - Size: 4392 / 14844 Offset: 1141323 Time: 1995/3/24 : 22h56m8s
EBATTLE7.MSG - Size: 3387 / 19440 Offset: 1145715 Time: 1995/3/24 : 22h56m8s
EBATTLE8.MSG - Size: 2975 / 10514 Offset: 1149102 Time: 1995/3/25 : 23h4m16s
EBATTLE9.MSG - Size: 1429 / 12983 Offset: 1152077 Time: 1995/3/10 : 23h1m44s
EBGMESS.MSG - Size: 16652 / 55642 Offset: 1153506 Time: 1995/3/25 : 22h23m50s
EDEBUG.MSG - Size: 14702 / 71632 Offset: 1170158 Time: 1995/2/8 : 19h55m44s
EEVENT0.MSG - Size: 19132 / 63696 Offset: 1184860 Time: 1995/3/25 : 22h23m52s
EEVENT1.MSG - Size: 20515 / 86914 Offset: 1203992 Time: 1995/3/25 : 22h54m14s
EEVENT2.MSG - Size: 20467 / 77397 Offset: 1224507 Time: 1995/3/25 : 22h23m54s
EEVENT3.MSG - Size: 19090 / 67271 Offset: 1244974 Time: 1995/3/25 : 22h54m14s
EEVENT4.MSG - Size: 17476 / 72250 Offset: 1264064 Time: 1995/3/25 : 22h54m16s
EEVENT5.MSG - Size: 15057 / 54545 Offset: 1281540 Time: 1995/3/24 : 16h42m48s
EEXPLGDS.MSG - Size: 21724 / 86868 Offset: 1296597 Time: 1995/3/25 : 22h54m16s
EEXPLPSI.MSG - Size: 4063 / 22040 Offset: 1318321 Time: 1995/3/22 : 16h34m2s
EGLOBAL.MSG - Size: 24590 / 90274 Offset: 1322384 Time: 1995/3/25 : 22h54m18s
EGOODS0.MSG - Size: 1964 / 8492 Offset: 1346974 Time: 1995/3/25 : 22h54m18s
EGOODS1.MSG - Size: 4011 / 12092 Offset: 1348938 Time: 1995/3/25 : 22h54m18s
EGOODS2.MSG - Size: 2750 / 7040 Offset: 1352949 Time: 1995/3/14 : 18h12m52s
EGOODS3.MSG - Size: 3833 / 12614 Offset: 1355699 Time: 1995/3/25 : 23h4m16s
EGOODS4.MSG - Size: 712 / 2375 Offset: 1359532 Time: 1995/3/16 : 18h17m14s
EHINT.MSG - Size: 19930 / 70281 Offset: 1360244 Time: 1995/3/25 : 22h54m20s
ENEWS.MSG - Size: 12238 / 48994 Offset: 1380174 Time: 1995/3/24 : 14h47m22s
ESHOP0.MSG - Size: 14236 / 100046 Offset: 1392412 Time: 1995/3/25 : 23h4m20s
ESHOP1.MSG - Size: 18412 / 97914 Offset: 1406648 Time: 1995/3/25 : 23h4m24s
ESHOP2.MSG - Size: 13526 / 50899 Offset: 1425060 Time: 1995/3/25 : 22h24m6s
ESHOP3.MSG - Size: 19141 / 79004 Offset: 1438586 Time: 1995/3/25 : 22h54m22s
ESYSTEM.MSG - Size: 15559 / 62871 Offset: 1457727 Time: 1995/3/25 : 23h4m28s

