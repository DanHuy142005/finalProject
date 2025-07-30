#!/bin/bash

# simple-interest.sh - Script tính lãi suất đơn

echo "Nhập số tiền gốc (P):"
read principal

echo "Nhập lãi suất (% mỗi năm) (R):"
read rate

echo "Nhập số năm (T):"
read time

# Tính lãi suất đơn: SI = (P * R * T) / 100
simple_interest=$(echo "scale=2; $principal * $rate * $time / 100" | bc)

echo "Lãi suất đơn (Simple Interest) là: $simple_interest"
