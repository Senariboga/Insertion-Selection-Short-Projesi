# Insertion-Selection Sort Projesi
## Insertion Sort Projesi:
### **[22,27,16,2,18,6]** dizisinin Insertion Sort'a göre adımları:
- 1st **[2,27,16,22,18,6]** (Dizideki en küçük olan 2 değeri 22 ile yer değiştirilerek en başa alındı)
- 2nd **[2,6,16,22,18,27]** (2 sabit, 27 ile 6 yer değiştirdi)
- 3rd **[2,6,16,22,18,27]** (2,6,16 sabit, 16 yerinde kaldı)
- 4th **[2,6,16,18,22,27]** (2,6,16 sabit, 22 ile 18 yer değiştirdi)
- 5th **[2,6,16,18,22,27]** (2,6,16,18,22 sabit, 27 yerinde kaldı)
- **Big-O : O(n^2)**
- **18 sayısı average case durumudur.**

## Selection Sort Projesi:

### **[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımı: 
```
- 1st **[2,3,5,8,7,9,4,15,6]** (Dizideki en küçük değer bulunarak en başa yazıldı, en baştaki veri ile yer değiştirdi), (7 değeri 2 ile yer değiştirdi)
- 2nd **[2,3,4,8,7,9,5,15,6]** (2,3 sabit kaldı, 5 ile 4 yer değiştirdi)
- 3rd **[2,3,4,5,7,9,8,15,6]** (2,3,4 sabit kaldı, 8 ile 5 yer değiştirdi)
- 4th **[2,3,4,5,6,9,8,15,7]** (2,3,4,5 sabit kaldı, 7 ile 6 yer değiştirdi)
```
- 5th **[2,3,4,5,6,7,8,15,9]** (2,3,4,5,6 sabit kaldı, 9 ile 7 yer değiştirdi)
- 6th **[2,3,4,5,6,7,8,9,15]** (2,3,4,5,6,7,8 sabit kaldı, 15 ile 9 yer değiştirdi)
