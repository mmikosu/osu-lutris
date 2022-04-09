lutris is literally the most broken website i swear

# osu! Lutris
A script that I made and tried to publish to Lutris, but Lutris is the most broken website to exist.

It (tries) to install osu! in Lutris, but due to how the osu! installer closes, it fails.

`osu-windows-fix.yaml` is an attempt to (somewhat) solve that issue.

Lutris wine builds seem to be broken when used on osu!, so I have included a specialized version of wine made by me.
The only modification is the gst-plugins, if you don't trust it, use your system's wine-staging.

I recommend you use pipewire to eliminate audio latency (and to just get rid of pulseaudio ew)

## PAY ATTENTION

The script uses wine-osu (the old wine 5 version) to stop the osu! installer from throwing an error and failing to install. **MAKE SURE** you change to (your system's) wine! (Lutris wine hasn't worked properly for me.)
