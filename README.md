# WaterVRTest
Experimental Water Shader for VR

*ITA:*

Esiste un grosso problema con lo shader WaterPRO dello Standard Asset di Unity.

Provandolo in VR semplicemente non funziona.

Cercando in rete si trovano alcune modifiche al codice di base:

- https://gist.github.com/miketucker/7253ec502f9ad205eee8a146481d6a74
- https://forum.unity.com/threads/reflection-rendering-wrong-in-openvr-htc-vive.398756/#post-3091506
- https://github.com/ValveSoftware/openvr/issues/251

E' giunto il momento di trovare la versione più corretta e soprattutto verificarla con gli ultimi aggiornamenti
per l'Oculus Rift e l'HTC Vive.

Esistono delle differenze negli shader proposti che devono essere studiati e verificati:

![Differenza Codice](https://github.com/Vytek/WaterVRTest/blob/master/Schermata%202017-10-18%20alle%2010.46.33.png)

*ENG:*

There is a big problem with the WaterPRO shader of Unity's Standard Asset.

Testing it in VR simply doesn't work.

When searching the network, you will find some changes to the base code:

- https://gist.github.com/miketucker/7253ec502f9ad205eee8a146481d6a74
- https://forum.unity.com/threads/reflection-rendering-wrong-in-openvr-htc-vive.398756/#post-3091506
- https://github.com/ValveSoftware/openvr/issues/251
It's time to find the most correct version and above all to check it with the latest updates for the Oculus Rift and the HTC Vive.

There are differences in the proposed shaders that need to be studied and tested:

![Diff](https://github.com/Vytek/WaterVRTest/blob/master/Schermata%202017-10-18%20alle%2010.46.33.png)

**RESULT for HTC Vive**

|Scene| Refraction  | Reflection |
|:-:|---|---|
| Scene1  | NOK | NOK |
| Scene2  | NOK | OK |

**Unity Version Used**

- Unity 2017.1.x
- Unity 2017.2.x
