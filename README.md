# NumClaim: A Dataset for Investor's Fine-grained Claim Detection
# Introduction
Numerals provide important information in financial narratives. Our statistical result in the financial analysis reports shows that over 58.47% of sentences contain at least one numeral. Without the numerals, lots of fine-grained information in the analysis reports will be lost. This phenomenon evidences the importance of the numerals in the financial narrative. Based on our observation, investors always make a claim with an estimation. This estimation can be a cue for detecting the investor's fine-grained claim. Therefore, we propose an expert-annotated dataset, NumClaim, for probing argument mining in the financial narrative. Among 5,144 instances in the NumClaim dataset, 23.78% and 76.22% of instances containing numerals are annotated as ``In-claim'' and ``Out-of-claim'', respectively.

# Format
The NumClaim dataset is consisted of "file", "text", "numeral", "offset", "category" and "in-claim" in json format.

# Example
```yaml
{

'file': 20181210_Jih-Sun-Securities-I_-----2385-TT---_1.pdf'

'text': '群光2019年動能推測以影像模組、高階鍵盤表現較佳，公司影像模組客戶包括G客戶與R客戶、Logitech、SportDV等，鍵盤輸入動能則來自於高階鍵盤包括平板外接、LED發光與電競鍵盤等出貨。群光1Q~3Q18一般鍵盤收入YoY-5%~-10%，高階鍵盤收入則超逾YoY+20%，主要係受惠於微軟Surface與電競需求增溫，而其電競客戶則包括Corsair、Logitech等，另外MSI、ASUS與中國品牌亦為供應商。群光2019年預期以電競鍵盤、LED發光鍵盤因市佔率提升而表現較佳。日盛預估群光2018年EPS5.03元，並預估2019年稅後EPS5.72元，群光2H18毛利率回溫，本益比僅約10倍，落於歷史低檔，維持買進評等。',

'numeral': '20',

'offset': 137,

'category': 'relative',

'in-claim': 0

}
```
# Download
Please write us an email with the agreement. Click [here](http://nlg.csie.ntu.edu.tw/nlpresource/NumClaim/NumClaim_agreement.pdf) to download the agreement of NumClaim.

Email Address: cjchen@nlg.csie.ntu.edu.tw

# How to Cite the Corpus
Please cite the following paper when referring to the NumClaim in academic publications and papers.

Chung-Chi Chen, Hen-Hsen Huang, and Hsin-Hsi Chen. 2020. NumClaim: Investor's Fine-grained Claim Detection. In Proceedings of the 29th ACM International Conference on Information and Knowledge Management (CIKM 2020), Virtual Event, Ireland.
# License
NumClaim is licensed under the [Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.
