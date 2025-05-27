# TechExcel: Copilot Studio で独自エージェントを開発する

このラボでは、Microsoft Copilot Studio を使用してカスタム AI 搭載カスタマーサービスエージェントを作成・強化する方法を学びます。新しいエージェントの作成、コンテンツの追加、Message ノードや Question ノード、エンティティ、スロットフィリング、変数など、対話型エージェント構築の基本を学びます。

進めていく中で、Power Automate を使って外部データソースやサービスと連携し、会話の中でデータを取得・返却する方法を体験します。HTTP リクエストノードの基本や、外部サービスから情報を取得する方法も理解できます。エージェントに自社サイトやナレッジソースを参照させることで、より賢く、正確な情報を提供できるようになります。カスタムプロンプト指示も活用します。

さらに、プラグインアクションを使った他データソースとの連携や、AI Builder プロンプトの呼び出しによる顧客フィードバック分析など、高度な機能も体験します。これらのスキルにより、複雑なタスクを処理し、貴重なインサイトを提供できる高機能なカスタマーサービスエージェントを構築できます。

このラボを通じて、Microsoft Copilot Studio を活用し、カスタマーサービスの効率化や組織の成長を支援する方法を理解できます。

## アーキテクチャ

![o2w1le2j.jpg](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/media/o2w1le2j.jpg)

## 演習

このラボには以下の演習が含まれます：

- Microsoft Copilot Studio で最初のエージェントを作成
- 基本的なオーサリングを学ぶ
- Power Automate クラウドフローをエージェントから呼び出す
- API へ HTTP リクエストを送信
- ナレッジソース、AI ナレッジ、カスタム指示の活用
- コネクタとの連携に生成 AI オーケストレーションを利用
- AI Builder プロンプトの呼び出し

## 前提条件

このラボを実施するには、以下が必要です：

- Dataverse 有効な Power Platform 環境
- Power Platform 環境内で有効化された Microsoft Copilot Studio トライアル サブスクリプション
- Power Automate
- Azure OpenAI サービスへのアクセス

## 顧客事例

Contoso, Inc. は、米国北西部の病院に特殊医療機器をリースしています。2005 年にシアトルで設立され、現在は 900 以上の病院と 15,000 人以上の個人をサポートしています。

近年、サービス需要の急増により、優れたカスタマーサービスと 24 時間以内のサービス契約対応を維持することが困難になってきました。従来のカスタマーサービス・サービス展開ツールでは対応しきれず、スタッフの負担増や業務効率の低下が課題となっています。

これらの課題を解決し、カスタマーサービスの効率化を図るため、Contoso, Inc. は Microsoft Copilot Studio を活用した新しい AI カスタマーサービスエージェントの導入を決定しました。これにより、現在および将来の業務負荷に対応し、機器メンテナンス依頼の管理プロセスを効率化し、顧客体験を向上させることを目指しています。

Microsoft Copilot Studio の機能を活用することで、カスタマーサービス担当者の負担軽減、応答時間の短縮、顧客への正確かつ迅速な情報提供が可能となります。この取り組みにより、Contoso は優れたカスタマーサービスの評判を維持し、医療機器リース業界での成長を支えます。

## 追加リンク

- [イントロダクション](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/)
- [演習 00: セットアップ](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/docs/Ex00/Ex00.html)
- [演習 01: Microsoft Copilot Studio で最初の Copilot を作成](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/docs/Ex01/Ex01.html)
- [演習 02: 基本的なオーサリングを学ぶ](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/docs/Ex02/Ex02.html)
- [演習 03: Power Automate クラウドフローをエージェントから呼び出す](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/docs/Ex03/Ex03.html)
- [演習 04: API へ HTTP リクエストを送信](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/docs/Ex04/Ex04.html)
- [演習 05: ナレッジソース、AI ナレッジ、カスタム指示の活用](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/docs/Ex05/Ex05.html)
- [演習 06: コネクタとの連携に生成 AI オーケストレーションを利用](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/docs/Ex06/Ex06.html)
- [演習 07: AI Builder プロンプトの呼び出し](https://microsoft.github.io/TechExcel-Designing-your-own-copilot-using-copilot-studio/docs/Ex07/Ex07.html)
- [Copilot Studio で独自 Copilot を設計する (GitHub)](https://github.com/microsoft/TechExcel-Designing-your-own-copilot-using-copilot-studio)

---

このサイトは [Just the Docs](https://github.com/just-the-docs/just-the-docs) テーマを利用しています。
