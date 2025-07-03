# Django サンプルアプリケーション

このリポジトリは、Python の Django フレームワークを使用したサンプルアプリケーションです。

## 概要

- Python + Django による基本的なWebアプリケーション構成を確認するためのテストプロジェクトです。
- 学習および開発検証用に作成しています。

## 注意事項

- このリポジトリには **Django のシークレットキーが含まれています** が、これはあくまで **ローカル開発・学習用途** のためであり、本番環境には使用しません。
- 本番環境では環境変数や Secrets Manager などで管理し、コードに直接含めないようにしてください。

---

## 使用技術

- Python
- Django

---

## セットアップ

```bash
git clone <repository-url>
cd <project-directory>
python -m venv venv
source venv/bin/activate  # Windows の場合は venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
