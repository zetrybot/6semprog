
ЛК4
# STDIN(0) - Стандартный ввод. Файл, из которого осуществляется чтение STDOUT - Стандартный вывод. Файл, в который осуществляется запись STDERR(2) - Стандартный поток ошибок

Перенаправление ввода command < filename Перенапраление вывода command>filename - rewrite command 1 > fulename command >>filename - append 2 >/dev/null - убирает поток ошибок

 # Процессы и потоки </br>
Процесс - набор ресурсов : память открытие файловых дескриторов контекст выполнения pid - уникальный индентификатор обработчики сигналов Код выхода Рабочий каталог Переменные окружения Состояния процесса

Потоки имеют: общую виртуальную память, каждый - свой виртуальный процессор</br>



# Вирутуальная файловая система </br>


# Появление процесса в системе </br>
init - создание процесса fork - копирование процесса fork - дочерний и родительский процесс Дочерний процесс - полная копия родительского, но получает управление первым А его PID присваивается родительскому процессу Адресное пространство родителя - совместное image Смерть процесса = команда kill Если родительский процесс завершился раньше дочернего, то у ребенка будет другой родитель
