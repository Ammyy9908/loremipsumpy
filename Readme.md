<h1>LoremipsumPy</h1>
# This Package Generates Placeholder Text i Python that can be use anywhere where you need to put some lorem ipsum

## Installation

Run the follwoing to install

pip install loremipsumpy

## Usage

from loremipsumpy import Lorem<br/>

lorem = Lorem()<br/>
data = lorem.get_lorem_default(count=1)<br/>
print(data)<br/>
data = lorem.get_lorem_large(count=1)<br/>
print(data)<br/>
data = lorem.get_xlarge(count=1)<br/>
print(data)<br/>
data = lorem.get_xxlarge(count=1)<br/>
print(data)
