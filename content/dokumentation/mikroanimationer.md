---
title: "Mikroanimationer"
date: 2018-02-01T08:53:19+01:00

---


<div class="loader">
    <div class="loading"></div>
</div>




Jeg har valgt en mikroanimation i form af et loading ikon der passer til mit havinspireret tema. Dette ikon er udført udelukkende via CSS og keyframes. 



Du kan se et udpluk af mine keyframes her:


```css
@keyframes wave {
    0% {
        border-radius: 25%;
    }
    100% {
        border-radius: 50%;
    }
}

@keyframes wave-after {
    0% {
        border-radius: 25%;
        left: -50px;
    }
    100% {
        border-radius: 50%;
        left: -42px;
    }
}

@keyframes wave-before {
    0% {
        border-radius: 25%;
        left: 44px;
    }
    100% {
        border-radius: 50%;
        left: 36px;
    }
}

@keyframes ocean {
    0% {
        top: 0;
    }
    100% {
        top: 10px;
    }
}

```

