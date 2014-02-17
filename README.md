Writing API


How to use this document?
Step I: Go through the document before you plan to develop API for your application.
Step II: Plan your implementation.
Step III: Read the document again. See if you comply with this doc as much possible.
Step IV: Develop.



Why is API Design Important?
Bad APIs result in unending stream of support calls
Public APIs are “forever” - one chance to get it right

Characteristics of a Good API
Easy to learn
Easy to use, even without documentation
Hard to misuse
Easy to read and maintain code that uses it
Sufficiently powerful to satisfy requirements
Easy to extend
Scope of arguments
No duplication
Generalized
Versioned

The Process of API Design
Gather Requirements–with a healthy degree of skepticism (try writing user stories)
Do not please everyone. Aim to displease everyone equally. Do not play with too many good-to-haves.
Count the number of API calls planned initially. Try if they can be further reduced. Re-iterate until possibility exist.
List down all the API call urls and verify if all user stories/requirement is met before commencing development.

General Principles
API should satisfy its requirements
API Should Do One Thing and Do it Well
Functionality should be easy to explain
If it's hard to name, that's generally a bad sign
You can always add, but you can never remove
Application development and maintenance should not Impact existing API
Names Matter–API is a Little Language. Be consistent–same word means same thing throughout API
Strive for symmetry
Document: Reuse is something that is far easier to say than to do. Doing it requires both good design and very good documentation
Return failure message upon failed request

