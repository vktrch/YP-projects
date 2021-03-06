{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "f1fcb088",
   "metadata": {},
   "source": [
    "# Анализ результатов A/B-теста\n",
    "\n",
    "Необходимо оценить корректность проведения теста, проанализировать его результаты.\n",
    "\n",
    "**Описание данных**\n",
    "\n",
    "ab_project_marketing_events.csv — календарь маркетинговых событий на 2020 год;\n",
    "- name — название маркетингового события;\n",
    "- regions — регионы, в которых будет проводиться рекламная кампания;\n",
    "- start_dt — дата начала кампании;\n",
    "- finish_dt — дата завершения кампании.\n",
    "\n",
    "final_ab_new_users.csv — все пользователи, зарегистрировавшиеся в интернет-магазине в период с 7 по 21 декабря 2020 года;\n",
    "- user_id — идентификатор пользователя;\n",
    "- first_date — дата регистрации;\n",
    "- region — регион пользователя;\n",
    "- device — устройство, с которого происходила регистрация.\n",
    "\n",
    "final_ab_events.csv — все события новых пользователей в период с 7 декабря 2020 по 4 января 2021 года;\n",
    "- user_id — идентификатор пользователя;\n",
    "- event_dt — дата и время события;\n",
    "- event_name — тип события;\n",
    "- details — дополнительные данные о событии. Например, для покупок, purchase, в этом поле хранится стоимость покупки в долларах.\n",
    "\n",
    "final_ab_participants.csv — таблица участников тестов.\n",
    "- user_id — идентификатор пользователя;\n",
    "- ab_test — название теста;\n",
    "- group — группа пользователя."
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
