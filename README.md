# tunika80

Параграф 80

1. Один из методов хэширования, который может минимизировать количество коллизий, — метод свёртки. Он предполагает деление элемента на кусочки одинаковой величины (последний из них может иметь отличающийся размер). Эти кусочки складываются вместе и дают результирующее хэш-значение.  

2. Блочный алгоритм шифрования — разновидность симметричного шифра, оперирующего группами бит фиксированной длины — блоками. Характерный размер которых меняется в пределах 64–256 бит. Если исходный текст (или его остаток) меньше размера блока, перед шифрованием его дополняют.

3. RSA — криптографический алгоритм с открытым ключом. RSA стал первым алгоритмом такого типа, пригодным и для шифрования и для цифровой подписи. Алгоритм используется в большом числе криптографических приложений. [источник?].

4. Цифровая подпись — это электронная зашифрованная печать, удостоверяющая подлинность цифровых данных, таких как сообщения электронной почты, макросы или электронные документы. Подпись подтверждает, что сведения предоставлены подписавшим их создателем и не были изменены.

5. Алгоритм RSA можно использовать для цифровой подписи следующим образом:  
   - Хэширование. Создаётся хэш сообщения или документа, который необходимо подписать. Это делается с помощью хэш-функции. 
   - Подпись. Значение хэша шифруется с использованием закрытого ключа подписывающего лица. В результате создаётся цифровая подпись, которая прикрепляется к исходному сообщению или документу.  
   - Проверка. Для проверки подлинности цифровой подписи получатель сообщения или документа должен сначала расшифровать подпись, используя открытый ключ подписывающего лица. При этом будет получено исходное значение хэша. Затем получатель вычисляет хэш-значение полученного сообщения или документа, используя ту же хэш-функцию, которая использовалась подписавшим лицом. Если два значения хэша совпадают, подпись действительна и сообщение или документ не были подделаны. 
