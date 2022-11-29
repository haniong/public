version = 'V1.1'
print(f'高级计算器 {version}')
print(f'请输入一个算式，符号和数之间记得留空格哟！')
print('输入“help”以获得更多信息')
while True:
    try:
        press = input('>')
        if press == 'help':
            print(f'''
                内置运算符号
                    加法：+
                    减法：-
                    乘法：*
                    除法：/
                    取余：%
                    次方：**
                注意事项
                    运算符号好数之间一定要留空格
                    如：1 + 1
                版本：{version}
                ''')
        else:
            s1 = int(press.split(' ')[0])
            og = str(press.split(' ')[1])
            s2 = int(press.split(' ')[2])
            if og == '+':
                print(s1 + s2)
            elif og == '-':
                print(s1 - s2)
            elif og == '*':
                print(s1 * s2)
            elif og == '/':
                print(s1 / s2)
            elif og == '%':
                print(s1 % s2)
            elif og == '**':
                print(s1 ** s2)
                
    except ValueError:
        print('请输入正确的数字')
    except IndexError:
        print('符号和数之间记得留空格哟！')
