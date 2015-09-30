# ConversionTrackerOperation
ConversionTrackerOperationオブジェクトは、操作の対象となるコンバージョントラッカー情報および操作の内容を表します。
### Service
+ [](../services/.md)

| フィールド | データ型 | 説明 | ADD | SET | 
|---|---|---|---|---|
| Operation(inherited)|||||
| operator| enum <a href="./Operator.md">Operator</a>| 処理を表す演算子です。| Req| Req |
| ConversionTrackerOperation|||||
| accountId| xsd:long| アカウントIDです。| Req| Req |
| operand| <a href="./ConversionTracker.md">ConversionTracker</a>| 操作対象コンバージョントラッカーのリストです。| Req| Req |
<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>
