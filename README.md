# Binary Trees

This repository contains a series of programs and functions for constructing, traversing, and manipulating binary trees. The project explores the core concepts of binary tree data structures and algorithms, offering practical insights into their implementation in C.

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Data Structures](#data-structures)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Examples](#examples)
- [Compilation](#compilation)
- [Author](#author)

---

## Introduction

Binary trees are fundamental data structures widely used in computer science for organizing and managing hierarchical data. This project implements a variety of binary tree operations, from creating nodes to traversing, deleting, and evaluating tree properties. It serves as a foundation for understanding more complex tree structures, such as binary search trees, AVL trees, and heaps.

---

## Features

- Create binary tree nodes.
- Perform tree traversal (in-order, pre-order, post-order, level-order).
- Evaluate binary tree properties (e.g., height, balance).
- Insert and delete nodes.
- Check for specific tree types (e.g., full, perfect, complete).
- Includes functions for both binary and binary search trees.

---

## Data Structures

The project uses the following structure to define binary tree nodes:

```c
typedef struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
} binary_tree_t;

