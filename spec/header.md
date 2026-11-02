# Virtual Private Knowledge (VPK) Protocol Specification

_Version:_ 0.1  
_Document Status:_ Working Draft  
_DOI:_ Not yet assigned  
_GitHub:_ <https://github.com/Kwaai-AI-Lab/vpk-protocol-specification>

_Editors:_

- Darren Warner, Kwaai

_Contributors:_

- None yet

**Abstract**

The Virtual Private Knowledge (VPK) Protocol lets the owner or custodian of data scramble it before transmitting it to an untrusted storage provider, so that the data remains encrypted at rest and searchable in its scrambled form. The data owner runs its own embedding model and keeps its documents locally. The storage provider stores only encrypted vectors and returns similarity scores, and never sees the documents, the plaintext queries or the embedding model.

**Intellectual Property Rights**

This specification is provided under the [Joint Development Foundation (JDF) charter](https://cdn.platform.linuxfoundation.org/agreements/ToIP.pdf) for [Trust Over IP](https://trustoverip.org) (ToIP) and is subject to the intellectual property rights policy of the **Decentralized Trust Graph Working Group**:

_Copyright:_ [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)  
_Patent:_ W3C Mode (based on the [W3C Patent Policy](https://www.w3.org/Consortium/Patent-Policy-20040205/))  
_Source Code:_ [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

THESE MATERIALS ARE PROVIDED “AS IS.” The parties expressly disclaim any warranties (express, implied, or otherwise), including implied warranties of merchantability, non-infringement, fitness for a particular purpose, or title, related to the materials. The entire risk as to implementing or otherwise using the materials is assumed by the implementer and user. IN NO EVENT WILL THE PARTIES BE LIABLE TO ANY OTHER PARTY FOR LOST PROFITS OR ANY FORM OF INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER FROM ANY CAUSES OF ACTION OF ANY KIND WITH RESPECT TO THIS DELIVERABLE OR ITS GOVERNING AGREEMENT, WHETHER BASED ON BREACH OF CONTRACT, TORT (INCLUDING NEGLIGENCE), OR OTHERWISE, AND WHETHER OR NOT THE OTHER MEMBER HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
