### Per base sequence content
>![m_bias_SRR5836473](https://github.com/evpryakhina/hhh/assets/147312734/49b7f90c-2cda-4011-9bec-e3dc261eca52)
>![per_base_SRR5836473_1](https://github.com/evpryakhina/hhh/assets/147312734/b0c7b011-a4c7-485e-9fb9-f4303e89dd61)
>![per_base_SRR5836473_1](https://github.com/evpryakhina/hhh/assets/147312734/5cabb810-3881-4222-9672-171ed2fb761d)
.png)
>![per_base_SRR3414630_1](https://github.com/evpryakhina/hhh/assets/147312734/83fddbfd-efb9-45f5-a5ab-5e0f1c083b18)



В `SRR5836473` сильно меньше цитоцина `C` чем в РНК, a тимина `T` больше. Гуанина `G` и ацетозин `А` также как в `SRR3414630`.

### Per sequence GC content
>![per_seq_SRR3414630_1](https://github.com/evpryakhina/hhh/assets/147312734/e9c33067-42e2-4ee5-8466-bf3e73f35c8a)
>![per_seq_SRR5836473_1](https://github.com/evpryakhina/hhh/assets/147312734/b65a56c3-f02a-427b-8f2f-5cf1f037bbea)
>![per_seq_SRR5836473_2](https://github.com/evpryakhina/hhh/assets/147312734/9b4f0f7b-84db-4465-956b-c96589f507c1)


У `SRR3414630` наблюдается нормальное распределение.

### Ipynb ноутбук
[Ссылка на collab](https://colab.research.google.com/drive/1ftUthNrbVSmB6BnRRgjSMIz-ik_7vIS6?usp=sharing)

### Число ридов
BS-Seq | ch11: 11347700-11367700 | ch11: 40185800-40195800 | deduplication 
--- | --- | --- | ---
SRR5836473 | 551 | 194 | 81.72%
SRR3824222 | 1344 | 565 | 97.09%
SRR5836475 | 797 | 274 | 90.93%

### M-bias plots

Получаем уровень метилирования каждой позиции в прочтении. (По 2 графика, т.к. парно-концевая запись)

#### SRR5836473 `8 Cell`
>![m_bias_SRR5836473](https://github.com/evpryakhina/hhh/assets/147312734/2e2ad9e9-52e2-452e-b755-1b6c57ff4d12)

#### SRR5836475 `ICM`
>![m_bias_SRR5836475](https://github.com/evpryakhina/hhh/assets/147312734/6f96c14e-bd9f-46f9-a9f8-dba524a2b5bb)


#### SRR3824222 `Epiblast`
>![m_bias_SRR3824222](https://github.com/evpryakhina/hhh/assets/147312734/434a6d05-e777-4482-86dd-f8076dae339d)


### Гистограмы распределения метелирования цитозинов по хромосоме

#### SRR5836473 `8 Cell`
>![hist_8cell](https://github.com/evpryakhina/hhh/assets/147312734/ec6f6dca-2d34-42f9-9472-cffcacc4d049)


#### SRR5836475 `ICM`
>![hist_icm](https://github.com/evpryakhina/hhh/assets/147312734/a7e4a42c-1dce-4a46-bc76-ade57a1defb3)


#### SRR3824222 `Epiblast`
>![hist_epiblast](https://github.com/evpryakhina/hhh/assets/147312734/29aa17cf-4099-4703-952a-018c6984ce0e)


#### Вывод:
Графики разнятся: 

1. В 8cell с ~40% вероятностью метилируется 0% цитозинов.
2. В icm с ~60% вероятностью метилируется 0% цитозинов.
3. В epiblast чаще всего метилируется 100% (это хорошо, т.к. метилирование принимает участие в экспрессии гена)

### Визуализация уровня метилирования и покрытия для каждого образца

#### Уровень Покрытия
>![image_cov](https://github.com/evpryakhina/hhh/assets/147312734/dcf368e8-114f-4112-b3ef-aecb3a670718)


#### Уровень Метилирования
>![image_met](https://github.com/evpryakhina/hhh/assets/147312734/78644248-2322-4c64-92a3-1165598e36ef)

