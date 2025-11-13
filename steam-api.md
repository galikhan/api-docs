### fetch user by phone number
#### GET method

```
https://my.steam.kz/api/v1/steam-telegram-bot-facade/user/7024819223
```

### upload results to api

#### POST method
```
https://my.steam.kz/api/v1/steam-telegram-bot-facade/project-and-labs
```

```
{
   user: <id>,
   uploadDate: <Данныйларды загрузка жасаган күні>,
   work: <ПРоект немесе лабканын id cы>,
   rating: <1-10 дейін жасалган рейтінг>,
   resourceUrl:<Optional> 
}

sample:
{
   user: 43,
   uploadDate: '2025-09-25T12:15',
   work: 22,
   rating: 9,
   resourceUrl:'https://drive.google.com/......' 
}

```

### fetch labworks and projects
#### GET method
```
https://my.steam.kz/api/v1/steam-telegram-bot-facade/project-and-labs/lang/ru/subject/22/class/14


subject { пән id }
class { сынып id }
```

### fetch category by lang and key
#### GET method
```
https://my.steam.kz/api/v1/steam-telegram-bot-facade/lang/ru/category/primary_classes

lang { ru, kk, en }
category { primary_classes,  middle_high_classes, quarter }
```
