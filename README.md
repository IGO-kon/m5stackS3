# m5stackS3



python -c "data=open('1.png','rb').read(); print('const unsigned char _1_png[] = {' + ','.join('0x%02x'%b for b in data) + '};'); print('const unsigned int _1_png_len = %d;' % len(data))" > image.h
