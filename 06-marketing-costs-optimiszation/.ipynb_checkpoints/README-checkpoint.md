{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "a3d822ad",
   "metadata": {},
   "source": [
    "# Оптимизация маркетинговых затрат в Яндекс.Афише\n",
    "\n",
    "На основе данных о посещениях сайта Яндекс.Афиши изучить, как люди пользуются продуктом, когда они начинают покупать, сколько денег приносит каждый клиент, когда он окупается\n",
    "\n",
    "**Описание данных**\n",
    "\n",
    "Файл visits_log.csv хранит лог сервера с информацией о посещениях сайта, orders_log.csv — информацию о заказах, а costs.csv — информацию о расходах на маркетинг.\n",
    "\n",
    "Структура visits_log.csv\n",
    "- Uid — уникальный идентификатор пользователя,\n",
    "- Device — категория устройства пользователя,\n",
    "- Start Ts — дата и время начала сессии,\n",
    "- End Ts — дата и время окончания сессии,\n",
    "- Source Id — идентификатор источника перехода на сайт.\n",
    "\n",
    "Структура orders_log.csv\n",
    "- Uid — уникальный идентификатор пользователя,\n",
    "- Buy Ts — дата и время заказа,\n",
    "- Revenue — сумма заказа.\n",
    "\n",
    "Структура costs.csv\n",
    "- source_id — идентификатор рекламного источника,\n",
    "- dt — дата проведения рекламной кампании,\n",
    "- costs — расходы на эту кампанию."
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
