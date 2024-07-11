# ML_Regression

# SHIFT_price_doc
Итоговый проект по курсу Машинное обучение в бизнесе

ML: sklearn, pandas, numpy 

Задача: Предсказать цену на квартиру price_doc
Представьте себе веб-приложение, которое может оценить стоимость недвижимости по объявлению. Какие особенности жилого объекта следует использовать для построения регрессионной модели прогнозирования цен? На основе некоторой информации требуется спрогнозировать цену объекта недвижимости. Необходимо провести разведочный анализ данных (EDA), придумать новые признаки на основе предложенных данных, поэкспериментировать с различными моделями машинного обучения, сделать с помощью этих моделей прогноз на тестовом датасете и загрузить ответы на страницу с результатами.

Evaluation Criteria

Результаты оцениваются метрикой RMSE.
Файл с результатами

Для каждого значения vin в тестовом датасете спрогнозируйте вероятность значения переменной price_doc. Файл должен содержать заголовок и иметь следующий формат:

,price_doc
0,1000000.0
1,2000000.0
2,3000000.0
etc.


Используемые признаки:

* full_sq
* num_room
* life_sq
* kitch_sq
* sub_area_num (from 0 to 145)
* ecology (from 0 to 4)
* big_road1_km
* church_synagogue_km
* oil_chemistry_km
* public_transport_station_min_walk
* public_transport_station_km
* railroad_station_avto_km
* product_type (0 or 1)
* railroad_station_walk_km
* railroad_station_walk_min
* kindergarten_km
* railroad_station_avto_min
* preschool_km
* school_km
* additional_education_km
* hospice_morgue_km
* ice_rink_km
* bus_terminal_avto_km
* big_road2_km
* power_transmission_line_km
* ts_km
* public_healthcare_km
* market_shop_km
* mosque_km
* shopping_centers_km
* metro_km_avto
* metro_km_walk
* metro_min_walk
* park_km
* fitness_km
* big_church_km
* metro_min_avto
* radiation_km
* museum_km
* euro_type (0 or 1: only for 1 or 2 num_room)
* exhibition_km
* workplaces_km
* thermal_power_plant_km
* swim_pool_km
* catering_km
* theater_km
* university_km
* detention_facility_km
* office_km
* basketball_km
* stadium_km
* nuclear_reactor_km
* ttk_km
* bulvar_ring_km
* kremlin_km
* zd_vokzaly_avto_km
* sadovoe_km

Model: XGBoostRegressor
©️ FAST, 2024. All rights reserved.​
