<body>
    <div class="article">
        <h1>Hello World</h1>
        <p>This is my first article. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eu ante a velit placerat posuere. Nulla facilisi. Sed auctor, nulla ac varius consequat, leo dolor venenatis nunc, eu tristique erat lectus vitae sem.</p>
        <p class="author">Author: 木渎席</p>
    </div>

import random

def generate_sentence():
    # 句子结构
    structure = [
        "主语动词宾语",
        "主语形容词",
        "主语动词副词",
        "主语动词宾语形容词",
        "主语动词副词副词"
    ]
    
    # 主语
    subject = [
        "我",
        "你",
        "他",
        "她",
        "它",
        "我们",
        "你们",
        "他们",
        "她们"
    ]
    
    # 动词
    verb = [
        "跑",
        "走",
        "看",
        "听",
        "吃",
        "喝",
        "写",
        "读"
    ]
    
    # 宾语
    object = [
        "书",
        "电影",
        "音乐",
        "食物",
        "水",
        "空气",
        "手机",
        "电脑"
    ]
    
    # 形容词
    adjective = [
        "美丽",
        "快乐",
        "悲伤",
        "幸福",
        "温暖",
        "可爱",
        "聪明"
    ]
    
    # 副词
    adverb = [
        "快速地",
        "慢慢地",
        "高兴地",
        "伤心地",
        "幸福地",
        "温暖地",
        "聪明地"
    ]
    
    # 随机选择句子结构
    sentence_structure = random.choice(structure)
    
    # 随机选择主语、动词、宾语、形容词、副词
    chosen_subject = random.choice(subject)
    chosen_verb = random.choice(verb)
    chosen_object = random.choice(object)
    chosen_adjective = random.choice(adjective)
    chosen_adverb = random.choice(adverb)
    
    # 根据句子结构生成句子
    if sentence_structure == "主语动词宾语":
        sentence = chosen_subject + chosen_verb + chosen_object
    elif sentence_structure == "主语形容词":
        sentence = chosen_subject + chosen_adjective
    elif sentence_structure == "主语动词副词":
        sentence = chosen_subject + chosen_verb + chosen_adverb
    elif sentence_structure == "主语动词宾语形容词":
        sentence = chosen_subject + chosen_verb + chosen_object + chosen_adjective
    elif sentence_structure == "主语动词副词副词":
        sentence = chosen_subject + chosen_verb + chosen_adverb + chosen_adverb
        
    return sentence

# 生成一句话
print(generate_sentence())


























