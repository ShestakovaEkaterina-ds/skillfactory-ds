﻿
→ Цель проекта подготовить данные для предсказательной модели (предсказывание оценки ученика по математике на госэкзаменах): 
  найти пустые значения, удалить выбросы, определить какие столбцы могут влиять на итоговую оценку.

→ данные содержат информацию об различных аспектах жизни ученика и его итоговая оценка за экзамен.

→ этапы работы над проектом:
  -- первичный визуальный осмотр данных
  -- так как количество столбцов большое, анализ как можно автоматизировать проверку колонок
  -- автоматическая проверка колонок с фиксированными значениями (проверка на корректность заполнения, замена пустых значений)
  -- ручная корректировка колонок с фиксированными значениями (там, где это необходимо)
  -- постороение графиков для колонок с фиксированными значениями
  -- ручной осмотр остальных столбцов (их, слава богу, немного)
  -- удаление выбросов в числовых столбцах
  -- постороение матрицы корреляций для числовых столбцов, анализ полученных результатов
  -- постороение боксплотов для номинативных признаков, анализ полученных результатов
  -- проверка статистически значимых различий у колонок с номинативными признаками
  -- окончательный вывод о том, какие колонки оставляем для построения модели предсказания 


