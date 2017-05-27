
INCLUDE_DIRECTORIES(
    ${CMAKE_CURRENT_SOURCE_DIR}
	include
	zbar
    ${TOPDIR}/prebuilts/thirdparty/libiconv-1.14/include
)

ADD_LIBRARY(zbar
	zbar/config.c
	zbar/convert.c
	zbar/decoder.c
	zbar/error.c
	zbar/image.c
	zbar/img_scanner.c
	zbar/processor.c
	zbar/refcnt.c
	zbar/scanner.c
	zbar/symbol.c
	zbar/decoder/codabar.c
	zbar/decoder/code128.c
	zbar/decoder/code39.c
	zbar/decoder/code93.c
	zbar/decoder/databar.c
	zbar/decoder/ean.c
	zbar/decoder/i25.c
	zbar/decoder/qr_finder.c
	zbar/qrcode/bch15_5.c
	zbar/qrcode/binarize.c
	zbar/qrcode/isaac.c
	zbar/qrcode/qrdec.c
	zbar/qrcode/qrdectxt.c
	zbar/qrcode/rs.c
	zbar/qrcode/util.c
)

