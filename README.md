***Разработка Web-приложений на языке Go***
======================================

### ***Комментарии переводчика***

Эта книга - русский перевод [《Go Web编程》](https://github.com/astaxie/build-web-application-with-golang), оригинальную версию которой написал [AstaXie](https://github.com/astaxie), а на английский язык перевели [Unknown](https://github.com/Unknwon) и [Larry Battle](https://github.com/LarryBattle). Русский перевод сделал [Alex Saskevich](https://github.com/asaskevich)

Эта книга о том, как разрабатывать приложения на языке Go. В первых разделах автор этой книги рассмотрит некоторые базовые концепции языка. Тем не менее, чтобы добиться максимальной пользы от чтения, Вам желательно иметь общее представление о языке Go и понимать концепцию веб-программирования. Заметим, что если Вы новичок, то эта книга не является вводным курсом, потому перед прочтением этой книги Вам желательно изучить другую литературу, например, книгу автора Caleb Doxsey [An Introduction to Programming in Go](http://www.golang-book.com/).

Если из-за качества перевода что-то оказалось недостаточно понятно, например по причине некорректности языковых формулировок, не стесняйтесь сообщить об этом мне на [репозитории перевода этой книги](https://github.com/asaskevich/build-web-application-with-golang_RU)

### Благодарности за помощь в переводе на английский язык

- [matalangilbert](https://github.com/matalangilbert)
- [nightlyone](https://github.com/nightlyone)
- [sbinet](https://github.com/sbinet)
- [carbocation](https://github.com/carbocation)
- [desimone](https://github.com/desimone)
- [reigai](https://github.com/reigai)
- [OlingCat](https://github.com/OlingCat)

### Цель этой книги

Так как я заинтересован в разработке Web-приложений, я использовал свое свободное время, чтобы написать эту книгу в версии с открытым исходным кодом. Но все же это не значит, что у меня хорошие знания в теме создания Web-приложений; я всего-лишь хотел бы поделиться теми навыками, которые получил при работе с языком Go, разрабатывая Web-приложения.

- Если вы PHP/Python/Ruby разработчик, то вы узнаете, как создавать приложения с помощью Go.
- Если вы C/C++ разработчик, вы узнаете, как работает сам Web, изнутри.

Я считаю, что самая главная цель изучения - обмен знаниями с другими. Потому что самая лучшая вещь в моей жизни -  делиться тем, что я знаю, с остальными людьми.

### Поддержка

Если вам понравилась эта книга, вы можете перейти по этой [ссылке](https://me.alipay.com/astaxie), чтобы поддержать оригинального автора, а также помочь ему написать еще больше книг с еще более полезным и интересным содержанием.

### Exchanging Learning Go

Если Вы знаете, что такое QQ, вступайте в нашу группу 259316004. Но если же нет, следуйте этой [ссылке](http://download.imqq.com/download.shtml), чтобы получить больше информации. Кстати, Вы также можете посетить наш [форум](http://bbs.beego.me).

### Благодарности

Во-первых, я хотел бы поблагодарить членов Golang-China в QQ группе #102319854, они оказали мне неоценимую помощь. Затем я хочу поблагодарить следующих людей, которые оказали большую помощь, когда я писал эту книгу.

 - [四月份平民 April Citizen](https://plus.google.com/110445767383269817959) (примеры кода)
 - [洪瑞琦 Hong Ruiqi](https://github.com/hongruiqi) (примеры кода)
 - [边  疆 BianJiang](https://github.com/border) (написал конфигурационные файлы к Vim и Emacs для разработки под Go)
 - [欧林猫 Oling Cat](https://github.com/OlingCat)(примеры кода)
 - [吴文磊 Wenlei Wu](mailto:spadesacn@gmail.com)(предложил некоторые картинки)
 - [北极星 Polaris](https://github.com/polaris1119)(пересмотрел всю книгу)
 - [雨  痕 Rain Trail](https://github.com/qyuhen)(пересмотрел разделы 2 и 3)

### Лицензия

This book is licensed under the [CC BY-SA 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/),
the code is licensed under a [BSD 3-Clause License](<https://github.com/astaxie/build-web-application-with-golang/blob/master/LICENSE.md>), unless otherwise specified.

## Ссылки

- [Содержание](preface.md)
