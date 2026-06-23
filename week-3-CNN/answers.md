# Week 3 - Part 1 Answers

## 1. Why does Laplacian highlight edges?
It computes second-order intensity changes. Large intensity changes occur at edges, producing strong responses.

## 2. Effect of increasing stride?
Larger stride reduces output size and computation, but loses spatial information.

## 3. Why does max pooling help translation invariance?
Small shifts in the input often keep the maximum activation within the pooling window unchanged.

## 4. Removing padding?
Output size shrinks and edge information near image boundaries is lost.
