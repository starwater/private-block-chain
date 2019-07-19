H8D+1BBJEwOmcdXm5ryfJjj+ASw00uEUXwI3ypkhYZRpJD8qho7G1cBxiZeXwwiWL5BqBc3su/4jWmSSq7pJuhs=


message: n2rCcMTstHT2HmcC1bGWhbEB5YxoMNDWrf:1563552449:starRegistry

legacy address: n2rCcMTstHT2HmcC1bGWhbEB5YxoMNDWrf



self.chain.filter(st => st.getBData()
                .then((res) => {
                    if (res.address === address) {
                        let star = res.star;
                        stars.push(star);
                        resolve(stars);
                    }
                }).catch((err) => {
                    console.log(err);
                    reject();
                }));

