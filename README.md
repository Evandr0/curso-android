# curso-android
#https://classroom.udacity.com/

android:text="Happy Birthday!"
android:layout_width = largura
android:layout_height = altura
android:layout_weight = Peso (Tamanho proporcional)
android:textSize = Tamanho do texto medido em sp. ex: 35sp
android:background="#33691E" (Cor do fundo)
android:textColor="#CCFF90" (Cor do texto)

android:id="@+id/lyla_text_view" *Cria um ID para a TextView* | serve para posicionar outros views em referencia a este.
android:layout_toRightOf="@id/lyla_text_view" - posiciona o objeto a direita do id lyla
android:layout_above="@id/jennie_text_view" = Acima do id jennie_text_view

android:layout_alignParentTop="true" | alinhamento da view com o "pai" no topo do device
android:layout_alignParentBottom="true"  = fundo
android:layout_alignParentRight="true" = Direita
android:layout_alignParentLeft="true" = esquerda




layout = wrap_content = acompanhará o tamanho do texto.
layout = match_parent = ocupara a tela toda.
