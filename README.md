# DataPositive
If StringInStr($delta, "-") = 0 Then ; positive      $iRow = _ArrayAdd($aAssetDataPositive, $aPublicAssets[$i] &amp; "|" &amp; $delta)  Else      $iRow = _ArrayAdd($aAssetDataNegative, $aPublicAssets[$i] &amp; "|" &amp; $delta)  EndIf  ; Now set the element to Number datatype  $aAssetDataPositive[$iRow][1] = Number($aAssetDataPositive[$iRow][1])
