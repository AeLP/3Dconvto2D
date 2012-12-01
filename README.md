3Dconvto2D
==========

3Dconvto2D　ワールド座標からスクリーン座標への変換 【行列を使わない考え方】

ワールド座標からスクリーン座標への変換

Download プログラム本体 3Dconvto2D.h https://github.com/downloads/AeLP/3Dconvto2D/3Dconvto2D.h 　プログラム解説 解説.pdf https://github.com/downloads/AeLP/3Dconvto2D/%E8%A7%A3%E8%AA%AC.pdf

使い方 #include "3Dconvto2D.h" して、s_Pos CamPos,Targetのx,y,zの値をどこかでセットしといてください 　　　　　s_Pos PのデータP.x,P.y,P.zが存在するとき

　　　　　ConvFromCam(P,&ScreenX,&ScreenY);でScreenX,ScrrenYにスクリーン座標が入ります

プログラム内の定数について 　　　　　ScDis　投影距離です。この値を大きくすると全体が小さく移ります 　　　　　ScWid 画面の横幅 ScHei 画面の縦幅

てきとーにどうぞ・・・