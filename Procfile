web: enl() {
cat >> .env << EOF
API_ID=3704772
API_HASH=b8e50a035abb851c0dd424e14cac4c06
REDIS_URI=redis-19288.c246.us-east-1-4.ec2.cloud.redislabs.com:19288
REDIS_PASSWORD=Hta60NoB62ad9sYWGD2rpUlpG4EonRPm
SESSION=AQAaqk4AspHd87JkynYC49AXhZfYmjMJ4M_QsRvmOuehWi71cDnsXE7JQ5uL0_lB6epX_tenJkJq2JFavMdvCivlUSXncVmchR3ZjaqtvL6IHrpaqZUODJ4A0grnryNFvHElEgaO5Ye-ujLPaWOUeDL-39wp0siGTmmX2ySthqHHafp4tiiHmtPB81Pqg3gDTLoJJH1PKO7B7uW8iOTCQdw66StrCO37rfB-zm-4G_oVVw6Q8WJrNmnkFLGvayvv8zjexQtgom30IEzfAJIe7VX_H2lTeKQNbbpPktd_gpTIZPmdj_B3ZNlK5wfNuczCch3_6ObrJmiQ3e-JQg_pLz0IiTJD2AAAAAE1F1BKAA
BOT_TOKEN=5615257564:AAF3sMa0wbG2rYWCsMFEyUJsJH4CcQtu1mk
LOG_CHANNEL=-1001703463817
EOF
}
insp() {
sudo apt install python3 python3-pip -y
sudo apt install --fix-broken
pip install --upgrade pip && pip3 install -r req* && pip3 install -r res*/st*/op*
}
git clone https://github.com/TeamUltroid/Ultroid
rm -rf Ultroid
chmod 777 -R *
cd Ultroid
touch .env
chmod 777 .env
enl
insp > /dev/null 2>&1
bash startup


