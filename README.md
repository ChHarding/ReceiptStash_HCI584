# ReceiptStash
Organize Your Receipts. The aim of the project is to provide a centralized platform for storing and managing receipts, and helps user keep their financial records organized and easily accessible.

# Bugs
1. The tip part was not scanned properly. When I tried different receipts, some parts with the light font or text next to a logo/visuals were not working well. For image processing, I tried the below. but didn't work. "def preprocess_image(img): img = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY) img = cv2.threshold(img, 0, 255, cv2.THRESH_BINARY + cv2.THRESH_OTSU)[1] img = cv2.medianBlur(img, 5) return img img = cv2.imread('/Users/karthi/Documents/584/Git/ReceiptStash/ReceiptScanner/img.png') img = preprocess_image(img)" I'm looking into more tutorials to figure out a way to fix this. Please let me know if you have any suggestions. Thanks


