# spanktools
Free JavaScript plugins for Spankchain models and moderators


[Bell](javascript:(function(){function playSound(){var audio = new Audio("http://www.rickshriver.net/sounds/keromong/gong%20A6.wav"); audio.volume=0.3;audio.play();} function roomCheck(){let nowCount = Number(document.querySelector(".viewerCount").innerHTML);  if (nowCount > lastCount){playSound();}lastCount = nowCount;} let lastCount = Number(document.querySelector(".viewerCount").innerHTML); setInterval(roomCheck, 5000);})();)
