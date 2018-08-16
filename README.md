<h5>turtlebot_arm_dynamixel</h5>
Turtlebot arm ကို arbotix controller မသုံးဘဲ dynamixel controller နဲ့သုံးချင်ရင် အခု package ကိုအသုံးပြုပါ
controller package ထဲက controller.launch က arm ကို စတင်ပေးပါ ပီးရင် moveit package ကိုဖန်တီးအသုံးပြုပါ
<br>
real robot နဲ့ အသင့်သုံးချင်ရင် <br>
turtlebot_arm_moveit_config ထဲက demo.launch ကို launch လုပ်ပါ <br>
controller.launch ကို သီးခြား launch လုပ်ရန်မလိုတော့ပါ
<br>
robot မရှိဘူး simulation အတွက်ပဲဆိုရင်တော့ demo.launch မှာ controller.launch include tag ကိုဖျက်ပီး joint state publisher တခုထဲ့ပေးပါ
ပီးရင် fake execution ကို true ထည့်ပေးပါ


