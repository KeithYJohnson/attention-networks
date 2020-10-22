Move trick because dl'd files coem with annoying prefix

for file in utf*;
do
    mv "$file" "/Users/kyj/play/attn-models/${file#utf-8\'\'}"
done
