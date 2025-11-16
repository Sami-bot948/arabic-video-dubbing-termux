bash
pkg update && pkg upgrade
pkg install python ffmpeg wget
pip install -r requirements.txt
pkg install wkhtmltopdf  # لتحويل HTML إلى PDF
