# PricePulse ChatSync
AI-powered price comparison chatbot that searches Takealot, Temu, Shein, Alibaba, Amazon ZA, RS Components, and more.

_By Mr. TT Jantjie_

flask
requests
beautifulsoup4
python-dotenv
openai
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "PricePulse ChatSync is live! - By Mr. TT Jantjie"

if __name__ == "__main__":
    app.run(debug=True)
git add .
git commit -m "Initial PricePulse ChatSync setup by Mr. TT Jantjie"
git push -u origin main
