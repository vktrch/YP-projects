{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "a26a5b6e",
   "metadata": {},
   "source": [
    "# Проект по SQL\n",
    "\n",
    "Необходимо ответить на поставленные в исследовании вопросы, применяя только SQL запросы, и используя библиотеку pandas только для хранения и вывода информации\n",
    "\n",
    "**Описание данных**\n",
    "\n",
    "Таблица `books` содержит данные о книгах:\n",
    "- book_id — идентификатор книги;\n",
    "- author_id — идентификатор автора;\n",
    "- title — название книги;\n",
    "- num_pages — количество страниц;\n",
    "- publication_date — дата публикации книги;\n",
    "- publisher_id — идентификатор издателя.\n",
    "\n",
    "Таблица `authors` содержит данные об авторах:\n",
    "- author_id — идентификатор автора;\n",
    "- author — имя автора.\n",
    "\n",
    "Таблица `publishers` содержит данные об издательствах:\n",
    "- publisher_id — идентификатор издательства;\n",
    "- publisher — название издательства;\n",
    "\n",
    "Таблица `ratings` содержит данные о пользовательских оценках книг:\n",
    "- rating_id — идентификатор оценки;\n",
    "- book_id — идентификатор книги;\n",
    "- username — имя пользователя, оставившего оценку;\n",
    "- rating — оценка книги.\n",
    "\n",
    "Таблица `reviews` содержит данные о пользовательских обзорах:\n",
    "- review_id — идентификатор обзора;\n",
    "- book_id — идентификатор книги;\n",
    "- username — имя автора обзора;\n",
    "- text — текст обзора."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.8"
  },
  "toc": {
   "base_numbering": 1,
   "nav_menu": {},
   "number_sections": true,
   "sideBar": true,
   "skip_h1_title": false,
   "title_cell": "Table of Contents",
   "title_sidebar": "Contents",
   "toc_cell": false,
   "toc_position": {},
   "toc_section_display": true,
   "toc_window_display": false
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
