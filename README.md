Студент: Казаков Анатолий
Ссылка на задание:   https://gb.ru/lessons/414942/homework
Решение задания №10 для Python (промежуточная аттестация) без использования get_dummies.
Задание было выполнено с учетом решений, показанных в записи:   https://disk.yandex.ru/i/XRU7vTDx62a8Yw

Текст задания:
В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца. Ваша задача перевести его в one hot вид. Сможете ли вы это сделать без get_dummies?
    import random
    lst = ['robot'] * 10
    lst += ['human'] * 10
    random.shuffle(lst)
    data = pd.DataFrame({'whoAmI':lst})
    data.head()
