<html>
<head>
<style>.button {
    display: inline-block;
    margin-bottom: 1rem;
    color: rgba(255,255,255,0.7);
    background-color: #159957;
    border-color: rgba(255,255,255,0.2);
    border-style: solid;
    border-width: 1px;
    border-radius: 0.3rem;
    transition: color 0.2s, background-color 0.2s, border-color 0.2s;
    padding: 0.75rem 1rem;
}
.discord {
    display: inline-block;
    margin-bottom: 1rem;
    color: rgba(255,255,255,0.7);
    background-color: #7289da;
    border-color: rgba(255,255,255,0.2);
    border-style: solid;
    border-width: 1px;
    border-radius: 0.3rem;
    transition: color 0.2s, background-color 0.2s, border-color 0.2s;
    padding: 0.75rem 1rem;
}</style>
</head>

<center><img src="./layout.png"></center>

<center><a href="https://ballerboo.github.io/boolayout/boo.zip" class="button">Download Boo Layout</a></center>
<center><a href="https://discord.gg/BKnzpGgua2" class="discord">Join the Boo Layout Discord</a></center>

</html>
    
# About Boo Layout

Boo Layout is designed for comfort at low and high speed, achieved with a decreased finger movement rate. This is accomplished with reduced SFB, DSFB, and LSB rates and distances.

Hand usage on Boo Layout is more balanced than popular alternative layouts such as Dvorak and Colemak.

Vowels are mostly concentrated on the left hand (a, e, o, u) to increase alternation and reduce redirects, while one vowel is placed on the right hand (i) to increase rolls.

The Boo Layout was initially created to rival the [ISRT Layout](https://notgate.github.io/layout/) which is based, among other things, on achieving low SFB% and higher index than pinky usage. ISRT was validated on the Colemakmods analyzer model. The Boo Layout scores very well, both on that model and [Semi's new Key Analyzer](https://github.com/semilin/genkey) which introduces novel analysis concepts.

There is also an AutoHotkey script that increases homerow usage by allowing the 'n' key location to be used to actuate the 'h' key for certain rolls. You can download this [here](https://ballerboo.github.io/boolayout/boo_ahk.zip).

You can use Boo layout on DreymaR's EPKL software [here](https://github.com/DreymaR/BigBagKbdTrixPKL/tree/master/Layouts/Boo).

# Analytics

## Stevep's analyzer

Below is a comparison of boo layout against other popular alternative layouts on SteveP's fork of patorjk's analyser.

![](stevep.png)

## Semi's analyzer

**Please note that Semi's analyzer is more accurate and more precise than SteveP's analyzer.**

Below is a detailed breakdown of boo layout from Semi's Key Analyser

- Rolls (left): 21.09%
  - Inward: ~10.39%
  - Outward: ~10.70%
- Rolls (right): 26.60%
  - Inward: ~12.80%
  - Outward: ~13.80%
- Alternates: ~30.55%
- Onehands: ~2.63%
- Redirects: ~10.10%
- Finger Speed (weighted): [0.59 0.34 1.22 2.16 1.96 1.52 1.84 0.96]
- Finger Speed (unweighted): [0.89 1.23 5.85 11.87 10.80 7.30 6.63 1.44]
- Highest Speed (weighted): 2.16 (LI)
- Highest Speed (unweighted): 11.87 (LI)
- Index Usage: 14.5% 17.2%
- SFBs: 0.935%
- DSFBs: 6.064%
- LSBs: 1.88%
- Top SFBs:
  - sc 0.138%
  - ue 0.129%
  - rk 0.123%
  - rl 0.077%
  - ph 0.070%
  - gs 0.061%
  - nf 0.060%
  - e' 0.048%
- Top DSFBs:
  - lk 13.398
  - ue 12.772
  - yi 11.385
  - lr 10.328
  - dm 10.048
  - cs 9.482
  - ,a 8.322
  - np 7.805
