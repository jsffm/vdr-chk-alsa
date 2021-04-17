Link asound.conf auf asound.conf.hdmi0 etc anlegen

asound.conf.hdmi0

<pre>
# HDMI
pcm.!default {
        type hw
        card 1
        #device 7
        device 3
}

ctl.!default {
       type hw
       card 1
}
</pre>

asound.conf.hdmi1

<pre>
# HDMI
pcm.!default {
        type hw
        card 1
        device 7
        #device 3
}

ctl.!default {
       type hw
       card 1
}
</pre>
