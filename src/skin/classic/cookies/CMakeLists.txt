build_macro_mkPaths()
FIND_FINAL_TARGET()

set(SRC_CSS_FILES
    ${mk_srcdir}/cookies.css
    ${mk_srcdir}/editCookie.css
    ${mk_srcdir}/trace.css
)

set(SRC_PNG_FILES
    ${mk_srcdir}/activation-menu-cookies.png
)

set(SRC_SVG_FILES
    ${mk_srcdir}/breakOnCookie.svg
    ${mk_srcdir}/cookie.svg
)

set(SOURCE_FILES
    ${SRC_CSS_FILES}
    ${SRC_PNG_FILES}
    ${SRC_SVG_FILES}
)

COPY_TO_DIST("${SOURCE_FILES}")
