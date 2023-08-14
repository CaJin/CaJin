import random

def generate_motivational_sentence():
    sentences = [
        "成功的关键在于坚持不懈地追求自己的目标，永不放弃。",
        "每一次努力都是一次成长的机会，不论结果如何，都要坚持向前。",
        "只有拥有勇气面对困难，才能获得真正的成就和快乐。",
        "相信自己的能力，勇敢地追求梦想，你将会创造出属于自己的辉煌。",
        "成功不是偶然，而是源于不断努力和智慧的结合。",
        "每一次挫折都是一次成长的机会，只要坚持不懈，你一定会取得成功。",
        "不要害怕失败，失败是成功的前奏，只要坚持下去，胜利一定属于你。",
        "每一次努力都是一种积累，即使看不到结果，也要相信自己正在进步。",
        "不要停下脚步，即使前路艰难，只要坚持走下去，你将会发现无限可能。",
        "相信自己的能力，勇敢地追逐梦想，你将会创造出属于自己的奇迹。"
    ]
    return random.choice(sentences)

# Generate daily motivational sentence
daily_sentence = generate_motivational_sentence()
print(daily_sentence)
