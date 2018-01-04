# liphdbpp-lite
Library for HDB++ implementing a LITE version of MySQL schema

Used only at ALBA-Synchrotron

## building
git clone --recursive http://github.com/tango-controls/libhdbpp-mysql.git  
cd libhdbpp-mysql  
export TANGO_DIR=/usr/local/tango-9.2.5a  
export OMNIORB_DIR=/usr/local/omniorb-4.2.1  
export ZMQ_DIR=/usr/local/zeromq-4.0.7  
make
