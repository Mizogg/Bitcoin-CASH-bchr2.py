# Bitcoin-CASH-bchr2.py
Random Scan for Bitcoin CASH BCH Addresses and Balance Using BITCASH Library and API Made in Python Automatically generate private key and address to check Balance. Requires internet Connection.

![image](https://user-images.githubusercontent.com/88630056/128643088-2ffbcd03-06c1-406d-973f-4c509345001d.png)

Full Information While Scan running:

---bchr2.py---Random Scan for Bitcoin CASH Addresses and Check Balance---------mizogg.co.uk---bchr2.py--- 2021-08-08 20:08:41.916524

<== Current PrivateKey (dec) ==> 80931931727880977228018905586532150406949156682060898384171151184365695843894

 <================================= Bitcoin CASH Addresses Checked for Balance =================================>

bitcoincash:qppdw7dn76d35p9ft8kap44l9s7908dyd5u6t0stst : b2edd99d854cfaff718ec4bc663901130d2e633578b0c4835373f17b8eb0be36 : L3DXScuj4iDbAd5j1iNQfWDiMLuBQ1b7VYnoCAd3M6wzo3D8zsjJ : 0
bitcoincash:qzylrp2zamn87du3276qhklw33d9t58h5vaymlwp8j : b2edd99d854cfaff718ec4bc663901130d2e633578b0c4835373f17b8eb0be36 : 5KB65u69dBhTmmsv24wEyJVi64bw1gZCSVxEdy6uBu6fUJ1Q15X : 0

Scan Number : 2093 : Total Wallets Checked : 4186
---bchr2.py---Random Scan for Bitcoin CASH Addresses and Check Balance---------mizogg.co.uk---bchr2.py--- 2021-08-08 20:08:43.474014

Edit Line 40 for range to scan.
ran= random.randint(1,115792089237316195423570985008687907852837564279074904382605163141518161494336)

If a Balance more than 0 is found winner.txt will be written and saved to current loction of bchr2.py with all the information to restore the Bitcoin CASH BCH wallet.

Made to run in python.
pip3 install bitcash
pip3 install colorama
