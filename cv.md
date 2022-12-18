![photo](/my_photo.jpg)
# Zemnovich Ruslan

## Contacts
  1. Telegram: @Nemiz1s
  2. Email: zemnovich@bk.ru
  3. Discord: Руслан(@nemizis)

## About me
I am a beginner in IT. I know python and some of its frameworks. For example: Pandas, numpy, sklearn, matplotlib, seaborn, tensorflow, django.
I am interested in front-end and data analysis in the field of CV.

## Hard-skills
* Python
  + Pandas
  + Numpy
  + sklearn
  + Matplotlib
  + Seaborn
  + Tensorflow
  + django
* IDE
  + I like jetbrains ide, like pycharm, dataspell
* Base HTML and CSS
* Bootstrap

## Code examples
link on git: https://github.com/nemizis/gallery
```
@transaction.atomic()
def auto_payment_unpaid(user: User):
    unpaid_orders = Order.objects.filter(user=user,
                                         status=Order.STATUS_WAITING_PAYMENT
                                         )
    for order in unpaid_orders:
        if Payment.get_balance(user) < order.amount:
            break
        order.payment = Payment.objects.all().last()
        order.status = Order.STATUS_PAID
        order.save()
        Payment.objects.create(user=user, amount=-order.amount)
```
## Experience
I have no commercial development experience.
pet-projects, volunteering.
I get data science skills on the skillbox platform and kaggle.
* Simple pet-project on django: https://github.com/nemizis/gallery
* Some EDA(Data science): https://colab.research.google.com/drive/1fkyrxPBVf9oHGokQrK1LZTaA9LqKfUfF

## Education
I learn on Skillbox.

## English level
I have B1 English level. But I don't have a lot of practice.

