{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "7d869348",
   "metadata": {},
   "source": [
    "# Проверка гипотез по увеличению выручки в интернет-магазине и оценка результатов A/B теста\n",
    "\n",
    "Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами\n",
    "\n",
    "**Описание данных**\n",
    "\n",
    "hypothesis.csv\n",
    "- Hypothesis — краткое описание гипотезы;\n",
    "- Reach — охват пользователей по 10-балльной шкале;\n",
    "- Impact — влияние на пользователей по 10-балльной шкале;\n",
    "- Confidence — уверенность в гипотезе по 10-балльной шкале;\n",
    "- Efforts — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.\n",
    "\n",
    "\n",
    "orders.csv\n",
    "- transactionId — идентификатор заказа;\n",
    "- visitorId — идентификатор пользователя, совершившего заказ;\n",
    "- date — дата, когда был совершён заказ;\n",
    "- revenue — выручка заказа;\n",
    "- group — группа A/B-теста, в которую попал заказ.\n",
    "\n",
    "visitors.csv\n",
    "- date — дата;\n",
    "- group — группа A/B-теста;\n",
    "- visitors — количество пользователей в указанную дату в указанной группе A/B-теста"
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
