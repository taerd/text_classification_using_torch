# text_classification_using_torch
example of text classification using pytorch
# В данном примере рассматривается задача текстовой классификации продукции (мясного отдела, https://axe.inline-ltd.ru/data/meatinfo.csv)
# После обработки датасета и выявления видов продукции ( у которых наблюдений больше >500) строится словарь и происходит embedding строк датасета.
# После embedding происходит создание и обучение текстового классификатора (на примере многослойного перцептрона), и на готовой модели происходит классифицирование тестового текста.
# Данный пример очень простой, в нем не затрагивалась fine tuning и глубокая обработка текста.
