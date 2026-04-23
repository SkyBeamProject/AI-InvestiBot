# Overview

AI-driven stock-prediction bot aiming to improve on typical trading bots via unique, non-daily indicators (including earnings) and flexible model construction. It exposes `PriceModel` and `PercentageModel` subclasses of a `BaseModel`, supports custom model callbacks, and uses a `ResourceManager` to allocate funds. Data comes from yfinance (cached as JSON via `get_info.py`), and deployment options include a loop script and an AWS Lambda version.
