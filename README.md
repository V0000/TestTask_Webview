# Тестовое задание Unity:

Написать приложение, которое содержит две части:
	1)	Экран с надписью "Hello"
	2)	Экран который открывает ссылку "https://google.com/"

Дополнительная логика: в случае если пользователь зашел в четное время (например 15:20), 
то показывать первый экран, в случае если в нечетное (15:13), то второй.
Результат первого захода сохранять, проверку при последующих заходах не повторять.
То есть если первый раз попали на первый экран - в дальнейшем пользователь должен
в любом случае попасть на первый экран. 


Постараться учесть все гайдлайны работы с webview:
	1. ВаскРressed. По нажатию на физическую кнопку “Назад" должна происходить навигация назад по стеку на сайте.
	Если страниц в стеке не осталось • должен происходить выход из приложения.
	2. No internet. В случае потери интернета во время серфинга в WebView должно показываться нативное окно,
	которое сообщает о потере интернета. По нажатию кнопки “Обновить" должна происходить повторная попытка загрузить страницу.

Результат задания: исходники и арк для теста.