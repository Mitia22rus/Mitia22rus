tests$ ./run.py
pip install gradio_clientimport { client } from "@gradio/client";

const app = await client("https://zhuraavl-mistralai-mistral-7b-v0-1.hf.space/");
const result = await app.predict("/predict", [		
				"Howdy!", // string  in 'Input' Textbox component
	]);

console.log(result.data);
def p(self, b=None):
    if b is None:
        b = self.a
    print b
