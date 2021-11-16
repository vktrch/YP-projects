{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "0d443289",
   "metadata": {},
   "source": [
    "# Продажа квартир в Санкт-Петербурге - анализ рынка недвижимости\n",
    "\n",
    "Используя данные сервиса Яндекс.Недвижимость, необходимо определить рыночную стоимость объектов недвижимости и типичные параметры квартир.\n",
    "\n",
    "**Задачи**\n",
    "\n",
    "- Первичное знакомство с данными\n",
    "- Предобработка данных\n",
    "- Добавление расчетных данных:\n",
    "    - цена квадратного метра\n",
    "    - день недели, месяц и год публикации объявления\n",
    "    - этаж квартиры; варианты — первый, последний, другой\n",
    "    - соотношение жилой и общей площади, а также отношение площади кухни к общей\n",
    "- Исследовательский анализ данных\n",
    "- Выводы\n",
    "\n",
    "**Описание данных**\n",
    "\n",
    "- airports_nearest — расстояние до ближайшего аэропорта в метрах (м)\n",
    "- balcony — число балконов\n",
    "- ceiling_height — высота потолков (м)\n",
    "- cityCenters_nearest — расстояние до центра города (м)\n",
    "- days_exposition — сколько дней было размещено объявление (от публикации до снятия)\n",
    "- first_day_exposition — дата публикации\n",
    "- floor — этаж\n",
    "- floors_total — всего этажей в доме\n",
    "- is_apartment — апартаменты (булев тип)\n",
    "- kitchen_area — площадь кухни в квадратных метрах (м²)\n",
    "- last_price — цена на момент снятия с публикации\n",
    "- living_area — жилая площадь в квадратных метрах (м²)\n",
    "- locality_name — название населённого пункта\n",
    "- open_plan — свободная планировка (булев тип)\n",
    "- parks_around3000 — число парков в радиусе 3 км\n",
    "- parks_nearest — расстояние до ближайшего парка (м)\n",
    "- ponds_around3000 — число водоёмов в радиусе 3 км\n",
    "- ponds_nearest — расстояние до ближайшего водоёма (м)\n",
    "- rooms — число комнат\n",
    "- studio — квартира-студия (булев тип)\n",
    "- total_area — площадь квартиры в квадратных метрах (м²)\n",
    "- total_images — число фотографий квартиры в объявлении"
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
