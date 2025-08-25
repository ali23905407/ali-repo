# ali-repo
just testing github
from flask import Flask, render_template_string

app = Flask(__name__)

@app.route('/')
def home():
    return render_template_string("<h1>سلام! به وب اپلیکیشن من خوش آمدید.</h1>")

if __name__ == '__main__':
    app.run(debug=True)
app
