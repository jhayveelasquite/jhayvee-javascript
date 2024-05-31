## Jhayvee-javascript
```
let nfts = [];

function mintNFT(name, age, section, gender) {
    const nft = {
        name: name,
        age: age,
        section: section,
         gender:  gender
    };
    nfts.push(nft);
}

function listNFTs() {
    for (let i = 0; i < nfts.length; i++) {
        console.log("Name: " + nfts[i].name);
        console.log("Age: " + nfts[i].age);
        console.log("Section: " + nfts[i].section);
        console.log("Gender: " + nfts[i].gender);
        console.log("------------------------- " );
    }
}

// Print the total number of NFTs we have minted to the console
function getTotalSupply() {
    return nfts.length;
}

mintNFT("Jhayvee", "20", "2.3 BSIT", "MALE");
mintNFT("Christian Lawrence", "20", "2.3 BSIT", "MALE");
mintNFT("Mark Josell", "19", "2.3 BSIT", "MALE");
mintNFT("John Xyriz", "23", "2.3 BSIT", "MALE");
listNFTs();
```
