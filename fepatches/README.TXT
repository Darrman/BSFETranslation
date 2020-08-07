These are ZSNES compatability patches for each of the four BSFE episodes.
Do not apply these if you are to use any other emulator!
Despite the original Japanese text suggesting the usage of an incredibly out-
dated version, these patches work fine with v1.51.
Apply to unheadered BSFE roms. (Do Satellaview dumps even have headers?)
Soft patching is recommended.
If Episode 1's rom is named "BSFE1.sfc", name the patch "BSFE1.ips".

DO NOT APPLY WITH OTHER EMULATORS!
THEY CAUSE ISSUES WITH THE CLOCK!

More specifially, they force it to 1:00, and it does not increment properly
outside of ZSNES. Other emulators use system time.

Original Japanese text is below.

	■ 「ＢＳファイアーエンブレム　アカネイア戦記編」用パッチセット ■

bsfm1.ips	「ＢＳファイアーエムブレム 第１話」用ＩＰＳパッチ
bsfm2.ips	「ＢＳファイアーエムブレム 第２話」用ＩＰＳパッチ
bsfm3.ips	「ＢＳファイアーエムブレム 第３話」用ＩＰＳパッチ
bsfm4.ips	「ＢＳファイアーエムブレム 第４話」用ＩＰＳパッチ

まず、ロムファイルにヘッダが付いている場合は、取ってください
そうしないとバイトのアドレスの関係でパッチが当たりません。

ロムファイルと拡張子以外同じ名前にして
ＺＳＮＥＳのＳＡＶＥディレクトリに入れてください
「ZSNES v0.800c」でないと動かないと思います

