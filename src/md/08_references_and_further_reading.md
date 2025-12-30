## یادداشت‌ها و منابع تکمیلی

### یادداشت‌ها

1. یک خوانندهٔ دقیق ممکن است متوجه شود که در واقع، آدرس بیت‌کوین هشِ کلید عمومی منحنی بیضوی (Elliptic Curve Public Key) است و نه خودِ کلید عمومی. با این حال، از نظر اصطلاحات رمزنگاری، اطلاق «کلید عمومی» به هشِ کلید عمومی کاملاً معتبر است. دلیل آن این است که رمزنگاری بیت‌کوین را می‌توان نوعی الگوریتم امضای دیجیتال سفارشی در نظر گرفت؛ جایی که کلید عمومی شامل هشِ کلید عمومی ECC است، امضا شامل خودِ کلید عمومی ECC به‌همراه امضای ECC بوده و الگوریتم اعتبارسنجی، ابتدا کلید عمومی ECC موجود در امضا را با هشِ ارائه‌شده به‌عنوان کلید عمومی تطبیق می‌دهد و سپس امضای ECC را با همان کلید عمومی بررسی می‌کند.

2. از نظر فنی، مقدار مورد استفاده، میانهٔ ۱۱ بلاک قبلی است.

3. در سطح داخلی سیستم، هر دو مقدار «۲» و «CHARLIE» عدد محسوب می‌شوند؛ با این تفاوت که مقدار دوم به‌صورت نمایش مبنای ۲۵۶ با ترتیب بایت big-endian ذخیره می‌شود. اعداد می‌توانند حداقل مقدار ۰ و حداکثر مقدار `2^256 - 1` را داشته باشند.

### منابع تکمیلی

1. **Intrinsic value**  
   https://tinyurl.com/BitcoinMag-IntrinsicValue

2. **Smart property**  
   https://en.bitcoin.it/wiki/Smart_Property

3. **Smart contracts**  
   https://en.bitcoin.it/wiki/Contracts

4. **b-money**  
   http://www.weidai.com/bmoney.txt

5. **Reusable proofs of work**  
   http://www.finney.org/~hal/rpow/

6. **Secure property titles with owner authority**  
   http://szabo.best.vwh.net/securetitle.html

7. **Bitcoin whitepaper**  
   http://bitcoin.org/bitcoin.pdf

8. **Namecoin**  
   https://namecoin.org/

9. **Zooko's triangle**  
   http://en.wikipedia.org/wiki/Zooko's_triangle

10. **Colored coins whitepaper**  
    https://tinyurl.com/coloredcoin-whitepaper

11. **Mastercoin whitepaper**  
    https://github.com/mastercoin-MSC/spec

12. **Decentralized autonomous corporations – Bitcoin Magazine**  
    https://tinyurl.com/Bootstrapping-DACs

13. **Simplified Payment Verification (SPV)**  
    https://en.bitcoin.it/wiki/Scalability#Simplifiedpaymentverification

14. **Merkle trees**  
    http://en.wikipedia.org/wiki/Merkle_tree

15. **Patricia trees**  
    http://en.wikipedia.org/wiki/Patricia_tree

16. **GHOST protocol**  
    http://www.cs.huji.ac.il/~avivz/pubs/13/btc_scalability_full.pdf

17. **StorJ and Autonomous Agents – Jeff Garzik**  
    https://tinyurl.com/storj-agents

18. **Mike Hearn on Smart Property (Turing Festival)**  
    http://www.youtube.com/watch?v=Pu4PAMFPo5Y

19. **Ethereum RLP**  
    https://github.com/ethereum/wiki/wiki/%5BEnglish%5D-RLP

20. **Ethereum Merkle Patricia Trees**  
    https://github.com/ethereum/wiki/wiki/%5BEnglish%5D-Patricia-Tree

21. **Peter Todd on Merkle Sum Trees**  
    http://sourceforge.net/p/bitcoin/mailman/message/31709140/
