Да се напише функция `calculate_coins(sum)`, която приема число с плаваща запетая и връща списък с монети. Целта е сумата да се представи с минималния брой монети.

Представете си, че сте касиерка във Фантастико и трябва да върнете по възможно най-малко неудобния начин ресто,
съставено само от монети. Очевидно - минималният брой монети е за предпочитане.

_Пример_:

    >>> calculate_coins(0.53)
    {1: 1, 2: 1, 100: 0, 5: 0, 10: 0, 50: 1, 20: 0}
    >>> calculate_coins(8.94)
    {1: 0, 2: 2, 100: 8, 5: 0, 10: 0, 50: 1, 20: 2}

Не мислете за каквито и да е проверки дали входът е валиден. Няма нужда вашият код да се държи адекватно при вход `(-42.0, 3.1415)`.
