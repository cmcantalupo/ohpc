TESTS_ENVIRONMENT       = BATS_NO_SUMMARY=1
TESTS                   = rm_execution\
                          test_module \
                          # end
check_PROGRAMS          = tutorial_4
tutorial_4_SOURCES      = Exception.hpp \
                          geopm_time.h \
                          Imbalancer.cpp \
                          imbalancer.h \
                          tutorial_4.c \
                          tutorial_region.c \
                          tutorial_region.h \
                          # end
tutorial_4_CPPFLAGS     = -I$(GEOPM_INC)
tutorial_4_LDFLAGS      = -L$(GEOPM_LIB) -lgeopm

