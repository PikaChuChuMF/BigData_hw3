# Альтернативы Spark на Python: Dask, Ray, Fugue

## Команда

Бойматов Юсуфджон, Сахневич Кирилл

## Описание

Этот репозиторий содержит материалы для презентации на тему "Альтернативы Spark на Python: Dask, Ray, Fugue". Презентация представляет собой обзор различных инструментов, предназначенных для параллельной обработки данных на Python, а именно Dask, Ray и Fugue. В презентации кратко рассматриваются основные возможности каждого инструмента, преимущества, а также сферы применения.

## Материалы

1. **presentation.slides**: [PDF презентации.](https://drive.google.com/file/d/1wThSratI8obOKzYP0_b23PguZUfXqK6m/view?usp=drive_link)

2. **Видео**: [Ссылка на видео.][(https://drive.google.com/file/d/1J1Wfqzb0GrIwKp-Wl_aRo51ISHsMFJ4S/view?usp=drive_link)

## Введение

Apache Spark долгое время был основным инструментом для обработки больших данных на Python. Однако появились альтернативы, предлагающие различные подходы к параллельной обработке данных и выполнению распределенных вычислений. Некоторые из таких альтернатив включают Dask, Ray и Fugue. В этом документе мы кратко рассмотрим каждую из них.

## Dask

[Dask](https://dask.org/) - это библиотека для параллельных вычислений в Python. Она предоставляет инструменты для создания графов вычислений и выполнения операций над данными, подобно тому, как это делается в Apache Spark. Однако, в отличие от Spark, Dask может использовать ресурсы на одной машине или на кластере. Dask также интегрируется хорошо с экосистемой Python, что делает его привлекательным выбором для Python-разработчиков.

Преимущества Dask:
- Простота использования и интеграция с экосистемой Python.
- Гибкость в настройке кластеров для различных задач.
- Поддержка различных типов данных и операций, включая массивы, фреймы данных и более сложные структуры данных.

## Ray

[Ray](https://ray.io/) - это распределенная платформа для выполнения вычислений в реальном времени. Она разработана для работы с параллельными и распределенными приложениями, предоставляя высокую производительность и масштабируемость. Ray имеет API для создания распределенных приложений, включая возможность создания асинхронных и параллельных задач.

Преимущества Ray:
- Высокая производительность и масштабируемость.
- Поддержка асинхронных операций и параллельных вычислений.
- Гибкая архитектура, позволяющая создавать различные типы распределенных приложений.

## Fugue

[Fugue](https://fugue-tv.github.io/) - это высокоуровневый фреймворк для обработки данных, который позволяет разработчикам описывать и выполнять вычислительные графы с помощью декларативного языка. Он предоставляет простой и удобный способ описания потоков данных и их преобразований. Fugue также интегрируется с различными инструментами обработки данных, такими как Apache Spark, Dask и Pandas.

Преимущества Fugue:
- Простой и понятный синтаксис для описания потоков данных.
- Интеграция с различными фреймворками обработки данных, что обеспечивает гибкость в выборе инструмента для выполнения задач.
- Поддержка декларативного подхода к описанию вычислительных графов.

## Заключение

Dask, Ray и Fugue - это три альтернативы Apache Spark на Python, каждая из которых предлагает свои уникальные особенности и преимущества. Выбор между ними зависит от конкретных требований проекта и предпочтений разработчика.
