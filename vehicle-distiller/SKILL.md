---
name: "vehicle-distiller"
description: "Distills real-world vehicles into GTA-style names and dealer descriptions. Invoke when user wants to convert a real vehicle into a GTA V style vehicle name and description."
---

# Vehicle Distiller

Transforms real-world vehicles into GTA V style vehicle names with Rockstar-style dealer descriptions.

## When to Use

Use this skill when:
- User provides a real-world vehicle name and wants a GTA-style conversion
- User asks to "蒸馏" (distill) a vehicle into GTA style
- User wants Rockstar-style vehicle names and satirical dealer descriptions

## How to Invoke

1. User provides real-world vehicle name
2. System searches for vehicle information
3. Generate GTA V style vehicle name
4. Generate Rockstar-style satirical dealer description

## Usage

```python
# Example usage
real_vehicle = "Ferrari 488 Spider"
# Output: GTA V style name + dealer description
```

## Output Format

Returns:
1. **GTA Style Name**: Created vehicle name following GTA naming conventions
2. **Dealer Description**: Satirical, humorous description in Rockstar's style
3. **Vehicle Class**: Sport, Muscle, Super, etc.
4. **Real World Reference**: Brief note on the real vehicle inspiration

## Rockstar Description Style Guidelines

- Humorous and satirical tone
- Often self-deprecating or making fun of wealthy buyers
- May reference game mechanics or upgrades
- Usually 2-4 paragraphs
- Often includes bullet points about features

## Text Style Variations (maintaining R-Star essence)

### Style A - The Contrarian
Present the vehicle as the opposite of what people expect, challenging conventional wisdom.

### Style B - The Pragmatist
Focus on practical benefits and real-world utility, downplaying luxury aspects.

### Style C - The Satirist
Use irony and sarcasm to highlight absurdities in car culture or ownership.

### Style D - The Enthusiast
Emphasize technical features and performance with genuine excitement.

### Style E - The Provocateur
Make bold, controversial statements that challenge the buyer's assumptions.

### Style F - The Realist
Acknowledge flaws while highlighting compensating strengths.

### Style G - The Conspirator
Suggest the vehicle is for those 'in the know', revealing hidden truths.

### Style H - The Minimalist
Use short, punchy sentences focusing on essential qualities.

### Style I - The Nostalgist
Reference classic vehicles or past eras, comparing to modern alternatives.

### Style J - The Philosopher
Contemplate the deeper meaning of vehicle ownership or transportation.

### Style K - The Analyst
Provide detailed technical breakdowns and performance metrics.

### Style L - The Storyteller
Frame the vehicle in narrative terms, suggesting adventures or scenarios.

### Style M - The Skeptic
Question the need for the vehicle while subtly promoting its benefits.

### Style N - The Visionary
Describe futuristic possibilities or advanced features.

### Style O - The Comedian
Use humor and puns to highlight vehicle characteristics.

## Feature Point Variations

- Military: "可加装导弹锁定干扰器", "可加装装甲板", "可加装机关炮升级", "可加装火箭弹发射巢", "可加装红外线夜视仪", "可加装隐形外壳涂层", "可加装电子对抗系统", "可加装烟雾弹发射器"
- Sport: "可加装高性能刹车系统", "可加装轻量化碳纤维套件", "可加装专业级排气系统", "可加装赛道悬挂", "可加装空气动力学套件", "可加装涡轮增压升级"
- Sedan: "可加装高级音响系统", "可加装氛围灯", "可加装真皮座椅", "可加装全景天窗", "可加装隐私玻璃", "可加装空气净化系统"
- SUV: "可加装越野轮胎", "可加装车顶行李架", "可加装涉水喉", "可加装底盘护板", "可加装绞盘", "可加装侧踏板"
- Bike: "可加装防摔护杠", "可加装风挡", "可加装边包", "可加装护膝", "可加装LED大灯", "可加装排气管护罩"
- Van: "可加装隔板", "可加装货架", "可加装冷藏箱", "可加装遮阳帘", "可加装车载冰箱", "可加装电源逆变器"