                            let currentAdsWatched = parseInt(localStorage.getItem('adsWatched')) + 1;
                    localStorage.setItem('earnings', earnings.toString());
                    localStorage.setItem('adsWatched', currentAdsWatched.toString());
                    alert(`(Test Mode) You earned BDT ${AD_REWARD.toFixed(2)}!`);
                    updateUI();
                }
            });

            withdrawForm.addEventListener('submit', (e) => {
