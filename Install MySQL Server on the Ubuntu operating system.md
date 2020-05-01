## Install MySQL Server on the Ubuntu operating system

​	 mysql  က open-source relational database  ျဖစ္ျပီ း open -source ျဖစ္လုိ႕ ေနရာေတာ္ေတာ္မွာ အသု့ံးျပဳပါတယ္ ၊ ခုေျပာမဲ့ အေၾကာင္းအရာ က ေတာ့ mysql  ကုိ ubuntu linux  မွာ setup or install ဘယ္လုိလုပ္မလဲ ဆုိ တာ တဆင့္ခ်င္း ရွင္းထားတာပါ ။  ဘယ္ commandline ေတြကုိ သုံးထားတယ္ဆုိတာကုိ တဆင့္ခ်င္းရွင္းျပထားပါတယ္္

 

<h1 style="font-size:30px"> Install MySQL
</h1>

အရင္ဆုံး အ ေနနဲ့  <span style="font-weight:bold"> terminal</span>  ကုိ ဖြင္ ့ျပီ းေအာက္ ျပ ထားတဲ့  ေအာက္ က ေပးထားတဲ ့ <span style="font-weight:bold"> command</span>  ကုိ ရုိက္ပါ။

 <div style="background-color:black;color:white; padding:20px;">
     <span>sudo apt-get update</span><br/>
     <span> apt-get install mysql-server</span>
</div>



y/n ေမးလာခဲ ့ရင္ y ကုိ ေျဖ ေပးပါ ပီးတဲ့ အထိ ေစာင့္ေပးပါ။

ေပးထားတဲ့ command ေတြက  အရင္ဆုံး စက္ထဲ မွာ ရွိတဲ့ software ေတြ ကုိ update လုပ္ ပီး <span style="font-weight:bold"> mysql-sever</span> နဲ့ဆုိငင္တဲ ့လုိအပ္တဲ့ dependenices ကုိ  ကုိ သြင္းတာပါ။ ခုဆုိရင္ install လုပ္ျပီး ျပီ လုိ ေျပာလုိ႔ရပါတယ္ အကုန္လုံးေတာ့ မဟုတ္ ေသးဖူး ေပါ့၊ secure ျဖစ္ေအာင္ လုပ္ေပးရ ပါဦးမယ္။ ေအာက္မွာ ေပးထားတဲ့ ကုိ ဆက္ပီး ကူထည့္ပါ၊



 <div style="background-color:black;color:white; padding:20px;">     
     <span> sudo mysql_secure_installation utility</span>
</div>



အ ေပၚမွာ ေပးထားတဲ့ ကုိ ရုိက္ ပီး ရင္utillity (setup လုပ္ဖုိ႕လုပ္ ေပးတဲ့ အရာ tools)ကုိ    secure ျဖစ္ေအာင္ လုပ္ ေပးမဲ့   <span style="font-weight:bold">root password  နဲ႔  root user </span> ကုိ configure လုပ္ ဖုိ႕ အတြက္ launch လုပ္ ေပး တာပါ၊ေနာက္  အ ေန နဲ့ 
