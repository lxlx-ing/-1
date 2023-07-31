# -1
#健康评估
weight=float(input('输入体重kg')) 
height=float(input('输入身高m'))
BMI=weight/height**2
man_best_weight=height*100-105
if BMI <=18.5:
    print(f'你偏瘦 最佳体重为 {man_best_weight}kg')
elif 18.5<BMI <23.9:
    print(f'你正常 最佳体重为 {man_best_weight}kg')
elif 24.0<=BMI<=28.0:
    print(f'你超重 最佳体重为 {man_best_weight}kg')
else:
    print(f'你肥胖 最佳体重为 {man_best_weight}kg')
