===============================================================================
=   Д о б р о   п о ж а л о в а т ь   в   у ч е б н и к   VIM  --  версия 1.7 =
===============================================================================
     
     Vim -- это очень мощный редактор, имеющий множество команд, слишком много
     для того, чтобы их все можно было описать в таком учебнике, как этот.
     Этот учебник призван объяснить достаточное число команд для того, чтобы
     вы могли с лёгкостью использовать Vim в качестве редактора общего
     назначения.

     Вам потребуется приблизительно 25-30 минут на освоение данного учебника в
     зависимости от того, сколько времени вы потратите на эксперименты.

     Внимание! Командами в уроках вы будете изменять этот текст. Создайте
     копию этого файла, чтобы попрактиковаться на ней (если вы запустили
     "vimtutor", то это уже копия).

     Важно помнить, что этот учебник предназначен для обучения в процессе
     использования. Это означает, что вы должны запускать команды для того,
     чтобы как следует их изучить. Если вы просто прочитаете этот текст, то
     не запомните команды!

     Теперь убедитесь в том, что клавиша CapsLock не включена, и нажмите
     клавишу  j  несколько раз, так, чтобы Урок 1.1 полностью поместился на
     экране.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                         Урок 1.1:  ПЕРЕМЕЩЕНИЕ КУРСОРА


** Для перемещения курсора нажмите клавиши h,j,k,l так, как показано ниже. **
             ^
             k          Советы: Клавиша h находится слева и перемещает влево.
       < h       l >            Клавиша l находится справа и перемещает вправо.
             j                  Клавиша j похожа на стрелку `вниз'.
             v
  1. Подвигайте курсор по экрану, пока не почувствуете себя уверенно.

  2. Надавите клавишу `вниз' (j) пока она не начнёт повторяться.
     Теперь вы знаете, как перейти к следующему уроку.

  3. Используя клавишу `вниз' перейдите к Уроку 1.2.

Замечание! Если вы пока не уверены в том, что набираете, нажмите <ESC> для
        перехода в обычный режим (Normal mode). После этого перенаберите
        требуемую команду.

Замечание! Обычные клавиши управления курсором (стрелки) также должны
        работать. Однако, клавиши hjkl позволят вам перемещаться
        значительно быстрее, как только вы научитесь ими пользоваться.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                      Урок 1.2: ЗАВЕРШЕНИЕ РАБОТЫ С VIM


  !! ВНИМАНИЕ! Прежде, чем выполнять любой из описанных ниже шагов, прочтите
                               урок целиком !!

  1. Нажмите клавишу <ESC> (для того, чтобы удостовериться, что вы в обычном
     режиме (Normal mode)).

  2. Наберите:                  :q! <ENTER>.
     (Это означает, что вы должны набрать три символа :q! и нажать клавишу
     ввод.) Это позволит вам выйти из редактора БЕЗ СОХРАНЕНИЯ любых сделанных
     изменений.

  3. Когда вы увидите приглашение командной оболочки, наберите команду,
     которая привела вас в этот учебник. Это может быть:
                                vimtutor <ENTER>

  4. Если вы уверены в том, что запомнили эти шаги, выполните шаги от 1 до 3
     чтобы выйти и снова запустить редактор.

Замечание!  :q! <ENTER>  отбрасывает любые сделанные вами изменения. Через
        несколько уроков вы узнаете как сохранять изменения в файл.

  5. Переместите курсор вниз к Уроку 1.3.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                  Урок 1.3: РЕДАКТИРОВАНИЕ ТЕКСТА -- УДАЛЕНИЕ


** Находясь в обычном режиме нажмите  x  для удаления символа под курсором. **

  1. Переместите курсор к строке ниже, помеченной --->.

  2. Для исправления ошибок, переместите курсор, пока он не окажется над
     удаляемым символом.

  3. Нажмите клавишу  x  для удаления требуемого символа.

  4. Повторите шаги со 2 по 4 пока строка не будет исправлена.

---> От топота копыт пыль по полю летит.

  5. Теперь, когда строка откорректирована, переходите к Уроку 1.4.

Замечание! В ходе освоения этого учебника не пытайтесь запоминать, учите
        в процессе использования.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                   Урок 1.4: РЕДАКТИРОВАНИЕ ТЕКСТА -- ВСТАВКА


       ** Находясь в обычном режиме, нажмите  i  для вставки текста. **

  1. Переместите курсор к первой строке ниже, помеченной --->.

  2. Для того, чтобы сделать первую строку идентичной второй, поместите
     курсор на символ ПЕРЕД которым следует вставить текст.

  3. Нажмите  i  и наберите требуемые добавления.

  4. После исправления всех ошибок нажмите <ESC> для возврата в обычный режим.
     Повторите шаги со 2 по 4, пока фраза не будет исправлена полностью.

---> Часть текста в этой строке бесследно пропала.
---> Часть текста в этой строке бесследно пропала.

  5. Когда освоите вставку текста, переходите к Уроку 1.5.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                 Урок 1.5: РЕДАКТИРОВАНИЕ ТЕКСТА -- ДОБАВЛЕНИЕ


     ** Находясь в обычном режиме, нажмите  A  для добавления текста. **

  1. Переместите курсор к первой строке ниже, помеченной --->.
     Не имеет значения на каком символе расположен курсор на этой строке.

  2. Нажмите  A  и наберите требуемые добавления.

  3. После добавления требуемого текста нажмите <ESC> для возврата в обычный
     режим.

  4. Переместите курсор на следующую строку, помеченную ---> и повторите шаги
     со 2 по 4 для исправления этой строки.

---> Часть текста в этой строке бесследно пропала.
     Часть текста в этой строке бесследно пропала.
---> Здесь также не достаёт части текста.
     Здесь также не достаёт части текста.

  5. Когда освоите добавление текста, переходите к Уроку 1.6.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                         Урок 1.6: РЕДАКТИРОВАНИЕ ФАЙЛА


        ** Используйте  :wq  для сохранения файла и выхода из Vim. **

  !! ВНИМАНИЕ! Прежде, чем выполнять любой из описанных ниже шагов, прочтите
                               урок целиком !!

  1. Выйдите из Vim, как вы это узнали в Уроке 1.2:  :q!
     Или, если у вас есть доступ к другому терминалу, можете сделать следующее
     в нём.

  2. По приглашению командной оболочки введите следующую команду:
                              vim tutor <ENTER>
     `vim' -- команда для запуска редактора Vim, а `tutor' -- имя файла для
     редактирования. Используете имя файла, который можно изменять.

  3. Вставляйте и удаляйте текст, как вы научились в предыдущих уроках.

  4. Сохраните файл с изменениями и выйдите из Vim выполнив:  :wq <ENTER>

  5. Если вы вышли из vimtutor на шаге 1, перезапустите vimtutor и переходите
     к следующему Резюме.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                                 РЕЗЮМЕ УРОКА 1


  1. Курсор перемещается либо клавишами со стрелками, либо клавишами hjkl.
        h (влево)       j (вниз)        k (вверх)       l (вправо)

  2. Для запуска Vim (из приглашения командной оболочки) наберите:
                            vim ИМЯ_ФАЙЛА <ENTER>

  3. Для завершения работы с Vim наберите:
        <ESC>   :q!   <ENTER>  чтобы отказаться от сохранения изменений.
     Или наберите:
        <ESC>   :wq   <ENTER>  чтобы сохранить изменения.

  4. Для удаления символа под курсором в обычном режиме, нажмите:  x

  5. Чтобы вставить текст перед курсором в обычном режиме, наберите:
         i   вводите вставляемый текст   <ESC>
     Чтобы добавить текст после курсора:
         a   вводите добавляемый текст   <ESC>

Замечание! Нажатие <ESC> переместит вас в обычный режим (Normal mode) либо
        прервёт нежелательную и частично завершённую команду.

Теперь переходите к Уроку 2.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
			   Урок 2.1: КОМАНДЫ УДАЛЕНИЯ


       ** Наберите  dw  для удаления участка текста до конца слова. **

  1. Нажмите <ESC>, чтобы перейти в обычный режим.

  2. Переместите курсор вниз, к строке помеченной --->.

  3. Переместите курсор в начало слова, которое следует удалить.

  4. Наберите  dw  для удаления этого слова.

Замечание! Во время набора буквы dw появятся справа в самой нижней строке
	экрана. Если вы что-то наберёте неправильно, нажмите <ESC> и начните
	сначала.

---> Несколько слов в этом предложении излишни.

  5. Повторите шаги 3 и 4, пока не исправите все ошибки и переходите к
     Уроку 2.2.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
		   Урок 2.2: ДОПОЛНИТЕЛЬНЫЕ КОМАНДЫ УДАЛЕНИЯ


	   ** Наберите  d$  для удаления текста до конца строки. **

  1. Нажмите <ESC>, чтобы перейти в обычный режим.

  2. Переместите курсор вниз, к строке помеченной --->.

  3. Переместите курсор к концу правильной строки (ПОСЛЕ первой точки).

  4. Наберите  d$  для удаления остатка строки.

---> Кто-то набрал окончание этой строки дважды.


  5. Чтобы лучше разобраться в том, как это происходит, переходите к Уроку 2.3.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
			  Урок 2.3: КОМАНДЫ И ОБЪЕКТЫ


  Многие команды, изменяющие текст, состоят из оператора и объекта. Формат
  команды удаления с оператором  d  следующий:

  	d   объект

  Здесь:
    d      - оператор удаления.
    объект - над чем должна быть выполнена команда (перечислено ниже).

  Краткий список объектов:
    w - от курсора до конца слова, включая последующий пробел.
    e - от курсора до конца слова, НЕ включая последующий пробел.
    $ - от курсора до конца строки.
    ^ - от курсора до начала строки.

Замечание! Простое нажатие на символ объекта в обычном режиме (Normal mode)
	без предварительного оператора переместит курсор так, как указано
	в списке объектов.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
		Урок 2.4: ИСПОЛЬЗОВАНИЕ СЧЁТЧИКА ДЛЯ ПЕРЕМЕЩЕНИЯ


      ** Ввод числа перед оператором перемещения приведёт к его повторению
			  заданное количество раз. **

  1. Переместите курсор к началу строки отмеченной ---> ниже.

  2. Наберите  2w  для перемещения курсора вперёд к началу второго слова.

  3. Наберите  3e  для перемещения курсора вперёд к концу третьего слова.

  4. Наберите  0  (нуль) для перемещения к началу строки.

  5. Повторите шаги 2 и 3 с различными числами.

---> Обычная строка из слов для вашего перемещения по ней.

  6. Переходите к Уроку 2.5.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
		 Урок 2.5: ИСПОЛЬЗОВАНИЕ СЧЁТЧИКА ДЛЯ УДАЛЕНИЯ


	    ** Ввод числа перед оператором приведёт к его повторению
			  заданное количество раз. **

  Добавьте число перед перед объектом в комбинацию оператора удаления и
  перемещения указанную выше для удаления указанного количества объектов:
	 d   число   объект

  1. Переместите курсор к первому слову из прописных букв в отмеченной --->
     строке ниже.

  2. Наберите  d2w  для удаления двух слов из прописных букв.

  3. Повторите шаги 1 и 2 с другими числами для удаления последовательных слов
     из прописных букв одной командой.

---> эта строка из слов очищена.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
			 Урок 2.6: ОПЕРАЦИИ СО СТРОКАМИ


		** Наберите   dd   для удаления целой строки. **

  В связи с частой необходимостью удаления целой строки, создатели Vi решили
  для упрощения сделать возможным удаление строки набором двух d.

  1. Переместите курсор вниз, ко второй строке фразы.

  2. Наберите dd для удаления строки.

  3. Теперь переместитесь к четвёртой строке.

  4. Наберите 2dd для удаления двух строк.

--->  1)  Летом я хожу на стадион,
--->  3)  Я болею за ``Зенит'', ``Зенит'' --- чемпион!
--->  6)  Я сижу на скамейке в ложе `Б'
--->  7)  И играю на большой жестяной трубе.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
			   Урок 2.7: КОМАНДА `ОТМЕНА'


  ** Нажмите  u  для отмены результата работы предыдущей команды, U для отмены
			 исправлений во всей строке. **

  1. Переместите курсор вниз, к строке помеченной --->, и установите его на
     первую ошибку.

  2. Нажмите  x  для удаления первого неправильного символа.

  3. Теперь нажмите  u  для отмены (отката) последней выполненной команды.

  4. Исправьте все ошибки в строке, используя команду  x .

  5. Теперь нажмите заглавную  U  для того, чтобы вернуть всю строку
     в исходное состояние.

  6. Нажмите  u  несколько раз для отмены команды  U  и предыдущих команд.

  7. Нажмите теперь CTRL-R (т.е. удерживайте клавишу CTRL нажатой в момент
     нажатия клавиши R) несколько раз для возврата команд (откат отката).

---> Испрравьте оошибки в этойй строке и вернитте их сс помощьью `отмены'.

  8. Это были очень полезные команды. Далее переходите к Резюме Урока 2.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
				 РЕЗЮМЕ УРОКА 2


  1. Для удаления текста от курсора до конца слова наберите:	dw

  2. Для удаления текста от курсора до конца строки наберите:	d$

  3. Для удаления всей строки наберите:		dd

  4. Для повтора перемещения введите количество перед командой:	2w 

  5. Формат команды в обычном режиме имеет вид:

       [число]   команда   объект     ИЛИ     команда	[число]   объект
     где:
       [число] - сколько раз повторить выполнение команды, опционально
       команда - что выполнить, например d для удаления
       объект  - на что должна воздействовать команда, например w (слово),
		$ (до конца строки), и т.д.

  6. Для перехода к началу строки используйте нуль:  0

  7. Для отмены (отката) предшествующих действий наберите:  u  (строчная u)
     Для отмены (отката) всех изменений в строке наберите:  U  (прописная U)
     Для отмены отката наберите:  CTRL-R

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
